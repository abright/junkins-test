pipeline {
    agent any
    stages {
        stage('something') {
            steps {
                checkout scm
                echo "running from branch: ${BRANCH_NAME}"
            }
        }
    }
    post {
        always {
            echo 'all done!'
        }
    }
}