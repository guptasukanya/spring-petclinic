pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'maven -X clean install'
      }
    }

  }
}