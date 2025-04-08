pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Docker image...'
                sh 'docker build -t my-jenkins-app .'
            }
        }

        stage('Test') {
            steps {
                echo 'Running dummy tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Docker container...'
                sh 'docker run -d -p 8081:80 --name my-jenkins-app my-jenkins-app || true'
            }
        }
    }
}
