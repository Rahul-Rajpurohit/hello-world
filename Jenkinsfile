pipeline{
    agent any
    stages{
        stage("Compile"){
            steps{
                echo "Hello!"
                cd First
                javac Hello.java
                java Hello
            }
        }
    }
}
