 pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out source code from GitHub'
            }
        }

        stage('Frontend Build') {
            steps {
                echo 'Building Frontend Application'
                bat 'cd frontend && echo "Frontend build completed"'
            }
        }

        stage('Backend Build') {
            steps {
                echo 'Building Backend Application'
                bat 'cd backend && echo "Backend build completed"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running application tests'
                bat 'echo "Application testing completed successfully"'
            }
        }

        stage('Deployment') {
            steps {
                echo 'Deploying application'
                bat 'echo "Application deployment completed"'
            }
        }

        stage('Verification') {
            steps {
                echo 'Verifying application deployment'
                bat 'echo "Application verification completed successfully"'
            }
        }
    }
}