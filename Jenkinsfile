pipeline {
    agent {
        docker {
            image 'node:18.10-bullseye-slim' 
            args '-p 3000:3000' 
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

