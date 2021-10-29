pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn pom.xml -e clean install'
      }
    }

  }
}