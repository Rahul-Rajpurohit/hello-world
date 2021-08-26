pipeline{
    agent any
    stages{
        stage("Compile"){
            steps{
                sh "javac Hello.java"
                sh "java Hello"
            }
        }
    }
}
