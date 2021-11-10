pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'maven -X clean install'
      }
    }

  }
  tools {
    maven 'maven'
  }
}