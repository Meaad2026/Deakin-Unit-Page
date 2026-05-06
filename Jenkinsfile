pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'if exist index.html (echo Test Passed) else (echo Test Failed)'
            }
        }
    }
}
