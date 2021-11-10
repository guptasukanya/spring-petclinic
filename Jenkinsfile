pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn -X clean install'
      }
    }

  }
  tools {
//     maven 'maven'
    mvn 'maven'
  }
}
