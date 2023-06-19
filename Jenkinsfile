pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building.."
              
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                bat "npm i"
                bat "npx cypress run"            
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver.... sadfasdfasdf'
                
            }
        }
    }
}