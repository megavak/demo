pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                bat "mvn clean  demo"
            }
        }
        stage('Test'){
            steps{
                bat "mvn clean test  demo"
            }
        }
        
        stage('Deploy'){
            steps{
                bat "mvn clean package  demo"
            }
        }
            
        }
    }
