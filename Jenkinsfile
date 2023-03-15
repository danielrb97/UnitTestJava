pipeline{
    agent any
    stages{
        stage("unit testing"){
            steps{
                dir("UnitTestJava/JavaTesting"){
                    sh "mvn clean compile test"
                }
            }
        }
    }
}
