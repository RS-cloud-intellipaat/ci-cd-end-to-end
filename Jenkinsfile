pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/RS-cloud-intellipaat/ci-cd-end-to-end.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t flask-app .'
            }
        }
    }
}
