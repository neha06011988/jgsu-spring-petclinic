pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                npm i
                npm run build
            }
        }
        stage('Test') { 
            steps {
                npm run test 
            }
        }
      }
}
