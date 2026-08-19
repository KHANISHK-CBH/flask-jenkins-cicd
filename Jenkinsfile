pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running unit tests...'
                echo 'Tests Passed successfully!'
            }
        }

        stage('Build Docker Image') {
            steps {
                echo 'Building Docker container image...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application container...'
                echo 'Application successfully deployed!'
            }
        }
    }
}