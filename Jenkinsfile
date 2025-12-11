pipeline {
    agent any // Runs on any available agent
    stages {
        stage('Build') {
            steps {
                echo "Building the project..."
                bat 'dir' // Windows command to list files
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                // Add your Windows test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying..."
                // Add your Windows deploy commands here
            }
        }
    }
}
