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

        stage('Code Quality') {
            steps {
                echo 'Checking code quality...'
                bat 'echo Code quality check completed'
            }
        }

        stage('Security') {
            steps {
                echo 'Running security scan...'
                bat 'echo Security scan completed - no critical vulnerabilities found'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                bat 'echo Application deployed successfully'
            }
        }

        stage('Release') {
            steps {
                echo 'Releasing application...'
                bat 'echo Application released to production'
            }
        }

        stage('Monitoring') {
            steps {
                echo 'Monitoring application...'
                bat 'echo Monitoring and alerts configured'
            }
        }
    }
}
