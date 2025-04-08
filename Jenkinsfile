pipeline {
    agent any

    stages {
        stage('Print Greeting') {
            steps {
                bat 'echo Hello from Jenkins Pipeline on Windows!'
            }
        }
        
        stage('Build') {
            steps {
                bat 'echo Simulating build step...'
                // For example: bat 'docker build -t my-app .'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests...'
                // Add any test commands if applicable
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying application...'
                // For example: bat 'docker run -d -p 8081:80 --name my-app my-app'
            }
        }
    }
    
    post {
        success {
            bat 'echo Pipeline completed successfully!'
        }
        failure {
            bat 'echo Pipeline failed. Check the logs for details.'
        }
    }
}
