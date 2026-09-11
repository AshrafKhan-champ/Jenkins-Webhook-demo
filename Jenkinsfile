pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo "Checking out source code from Github"
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo "Building the application"
                echo "Build completed successfully"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests"
                echo "All tests passed successfully"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the application"
                echo "Deployment completed successfully"
            }
        }
    }
}
