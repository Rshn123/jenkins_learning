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
                bat "npx cypress run --browser chrome --spec cypress/e2e/*/*.cy.js"            
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver.... sadfasdfasdf'
                
            }
        }
    }
}