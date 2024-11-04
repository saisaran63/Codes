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
                sh 'echo Building project...'
                // Add your build commands here
            }
        }
}
