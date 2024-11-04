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
        stage('Test') {
            steps {
                sh 'echo Running tests...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying application...'
                // Add your deployment commands here
            }
        }
    }
    post {
        always {
            echo 'Cleaning up...'
            cleanWs() // Cleanup workspace after build
        }
    }
}
