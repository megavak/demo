pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                bat "mvn clean -f demo"
            }
        }
        stage('Test'){
            steps{
                bat "mvn clean test -f demo"
            }
        }
        
        stage('Deploy'){
            steps{
                bat "mvn clean package -f demo"
            }
        }
            
        }
    }
