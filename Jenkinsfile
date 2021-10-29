pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn pom.xml clean install'
      }
    }

  }
}