pipeline {
    agent {
        docker {
            image 'python:latest'
            args '-u root'
        }
    }
    stages {
        stage('Install Dependencies') {
            steps {
                script {
                    sh 'pip install -r requirements.txt'
                }
            }
        }
    }
}