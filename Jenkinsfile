pipeline {
 agent any // Runs on any available agent
 stages {
 stage('Build') {
    steps {
        bat 'echo Building the project...'
        bat 'your-windows-command-here'
    }
}
 stage('Test') {
 steps {
 echo "Running tests..."
}
 }
 stage('Deploy') {
 steps {
 echo "Deploying..."
 }
 }
 }
}