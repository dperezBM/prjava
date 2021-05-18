pipeline {
  agent any

  stages {
    stage('compilar') {
      steps {
        sh 'javac Simple.java'
      }
     }
    stage('ejecutar'){
      steps{
        sh 'java Simple'
      }
    }
  }
}
