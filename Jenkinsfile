#!groovy
pipeline {
  agent none
  stages {
    stage('Docker Build') {
      agent { Dockerfile true }
      steps {
        sh 'docker build -t anitbibin/sandbox-ui .'
      }
    }
  }
}
