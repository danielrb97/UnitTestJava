pipeline{
    agent any
    stages{
        stage("unit testing"){
            steps{
                sh "mvn clean compile test"
            }
        }
    }
}