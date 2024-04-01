pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/MaleehaYounas/SCD_lab10'
            }
        }
        
        stage('Dependency Installation') {
            steps {
                sh 'npm install'
            }
        }
        
        stage('Build') {
            steps {
                sh 'node server.js'
            }
        }
        
        stage('Test') {
            steps {
                sh 'echo test'
            }
        }
        
        stage('Deployment') {
            steps {
                sh 'echo docker'
            }
        }
    }
}
