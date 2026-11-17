pipeline {
    agent any

    stages {
        stage('Build Docker') {
            steps {
                sh 'docker compose up -d --build'
            }
        }
        
    }
}