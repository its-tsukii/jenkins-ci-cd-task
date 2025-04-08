pipeline {
    agent any

    stages {
        stage('Preparation') {
            steps {
                bat 'echo Preparing the build...'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building the application...'
                // Add your actual build steps here, like compiling code or running scripts
            }
        }

        stage('Test') {
            steps {
                bat 'echo Running tests...'
                // Add testing commands here
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying application...'
                // Add deployment steps if any
            }
        }
    }

    post {
        success {
            bat 'echo Pipeline completed successfully.'
        }
        failure {
            bat 'echo Pipeline failed. Check the logs for details.'
        }
    }
}
