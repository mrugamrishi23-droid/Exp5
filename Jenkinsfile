pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                sh 'javac --release 17 HelloWorld.java'
            }
        }

        stage('Run Java') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
