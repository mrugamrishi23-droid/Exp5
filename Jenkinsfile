pipeline {
    agent any
    stages {
        stage('compile'){
            steps{
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run Python') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
