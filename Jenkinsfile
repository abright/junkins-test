pipeline {
    agent any
    stages {
        stage('something') {
            steps {
                checkout scm
                echo "running from branch: ${BRANCH_NAME}"
            }
        }
        stage('some master') {
            when {
                branch 'master'
            }
            steps {
                echo "we master now"
            }
        }
        stage('some release') {
            when {
                branch 'release'
            }
            steps {
                echo "we release now"
            }
        }
    }
    post {
        always {
            echo 'all done!'
        }
    }
}