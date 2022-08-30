pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                npm i
                npm run lint
                npm run build
            }
        }
        stage('Test') { 
            steps {
                npm run test 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
    
