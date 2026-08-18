pipeline {
  agent any
stages {
  stage('compile') {
    steps {
      sh 'javac Addition.java'
    }
}
stage('Run'){
  steps {
    sh 'java Addition'
  }
}
}
}
