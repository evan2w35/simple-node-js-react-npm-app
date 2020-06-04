pipeline {
    agent {
        docker {
            image 'node:7-alpine' 
            args '-p 50000:50000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}