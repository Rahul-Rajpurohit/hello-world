pipeline{
    agent any
    stages{
        stage("Compile"){
            steps{
                sh "git clone https://github.com/Rahul-Rajpurohit/hello-world.git"
                sh "cd hello-world"
                sh "javac Hello.java"
                sh "java Hello"
            }
        }
    }
}
