pipeline{
    agent any
    stages{
        stage("unit testing"){
            steps{
                dir("UnitTestJava"){
                    sh "mvn clean compile test"
                }
            }
        }
    }
}