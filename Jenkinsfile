pipeline {
    agent any
    stages {
        stage('something') {
            always {
                echo 'something goes here'
            }
        }
        stage('something else') {
            always {
                echo 'something else goes here'
            }
        }
    }
    post {
        always {
            echo 'all done!'
        }
    }
}