pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                echo 'Compiling the java code'
                sh javac Hello.java
            }
        }
        stage('Run Java') {
            steps {
                echo 'Run the java code'
                sh java Hello
            }
        }
    }
}