pipeline{
    agent any
    stages{
        stage("unit testing"){
            steps{
                dir("JavaProjectTest"){
                    sh "mvn clean compile test"
                }
            }
        }
    }
}
