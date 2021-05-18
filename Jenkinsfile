pipeline {
  agent any
  environment {
    NOMBRE = "test"
  }
  stages {
    stage('compilar') {
      steps {
        sh 'javac Param.java'
      }
     }
    stage('ejecutar'){
      steps{
        sh 'java Param ${NOMBRE}'
      }
    }
  }
}
