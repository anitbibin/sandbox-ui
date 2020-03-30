#!groovy
pipeline {
  agent none
  stages {
    stage('Docker Build') {
      agent { dockerfile true }
      steps {
        sh 'docker build -t anitbibin/sandbox-ui .'
      }
    }
  }
}
