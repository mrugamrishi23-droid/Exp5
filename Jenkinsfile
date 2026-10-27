pipeline {
    agent any
    stages {
        stage('compile'){
            steps{
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run java') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
