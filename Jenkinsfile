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
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying application...'
            }
        }
    }
}
