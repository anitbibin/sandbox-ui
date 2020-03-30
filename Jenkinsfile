#!groovy
pipeline {
  agent none
  stages {
    stage('Docker Build') {
      agent { dockerfile true }
      steps {
        echo 'deploying...'
      }
    }
  }
}
