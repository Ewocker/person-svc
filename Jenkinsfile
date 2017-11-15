pipeline {
  agent {
    node {
      label 'slave'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }
    stage('Test') {
      steps {
        sh '''echo "i am a test"
exit 0'''
      }
    }
  }
}