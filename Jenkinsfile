
pipeline {
    agent any

    tools {
        jdk 'Java 21'
    }

    stages {
        stage('Compile') {
            steps {
                echo 'Compiling...'
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Running...'
                bat 'java HelloWorld'
            }
        }
    }
}
