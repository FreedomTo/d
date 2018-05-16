pipeline {
  agent any
  stages {
    stage('verify file') {
      steps {
        fileExists 'a.c'
      }
    }
  }
}