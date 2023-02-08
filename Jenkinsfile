pipeline {
    agent {
        docker{
            image 'node:lts-bullseye-slim'
            arges '-p 3000:3000'
        }
    }
    
    stages{
        stage('Build'){
            steps {
                sh 'npm install'
            }
        }
    }
}