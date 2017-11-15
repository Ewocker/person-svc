pipeline {
  agent {
    node {
      label 'slave'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn --quiet clean package'
      }
    }
  }
}