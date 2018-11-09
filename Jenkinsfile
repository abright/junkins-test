pipeline {
    agent any
    stages {
        stage('something') {
            steps {
                def gitvars = checkout scm
                echo 'running from branch: ${gitvars.GIT_BRANCH}'
            }
        }
    }
    post {
        always {
            echo 'all done!'
        }
    }
}