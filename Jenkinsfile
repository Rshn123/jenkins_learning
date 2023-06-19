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
                cd "cypress"
                npx cypress run
               
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver.... sadfasdfasdf'
                
            }
        }
    }
}