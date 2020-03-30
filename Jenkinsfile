pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('master') {
      steps {
        sh 'docker build -t anitbibin/sandbox-ui .'
      }
    }
    stage("Docker build") {
      steps {
        sh "docker build -t anitbibin/sandbox-ui ."
      }
    }
  }
}
