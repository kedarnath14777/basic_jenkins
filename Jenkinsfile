pipeline {
    agent {
        label 'agent-1'
    } 
    stages{
        stage ('Build'){
            steps{
                echo "this the buils stage."
            }
        }
        stage ('test'){
            steps{
                echo "this is the test  stage"
            }
        }
        stage ('Deploy'){
            steps{
                echo "this is the ust stage"
            }
        }
        stage('production'){
            steps{
                echo "this is the production satge "
            }
        }
    }
}