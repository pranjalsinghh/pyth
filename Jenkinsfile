pipeline{
    agent any
    stages{
        stage ('Testing'){
            steps{
                echo 'running test'
                sh 'mvn test'
            }
        }
        stage ('Build'){
            steps{
                echo 'Hello'
                sh 'mvn package'
            }
        }
    }
    
    
}
