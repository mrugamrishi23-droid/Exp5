pipeline {
    agent any

    stages {

        stage('Run Python') {
            steps {
                sh 'python3 Myname.py'
            }
        }

        stage('Compile Java') {
            steps {
                sh 'javac Addition.java'
            }
        }

        stage('Run Java') {
            steps {
                sh 'java Addition'
            }
        }

    }
}
