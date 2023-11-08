pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                echo 'Compiling the java code'
                javac Hello.java
            }
        }
        stage('Run Java') {
            steps {
                echo 'Run the java code'
                java Hello
            }
        }
    }
}