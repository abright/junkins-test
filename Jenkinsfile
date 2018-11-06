pipeline {
    agent any
    stages {
        stage('something') {
            steps {
                echo 'something goes here'
            }
        }
        stage('something else') {
            steps {
                echo 'something else goes here'
            }
        }
    }
    post {
        steps {
            echo 'all done!'
        }
    }
}