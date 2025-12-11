pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building the project...'
                // Run your actual build command here, e.g., npm install
                bat 'npm install'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests...'
                // Run your actual test command
                bat 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying project...'
                // Run your actual deploy command
            }
        }
    }
}
