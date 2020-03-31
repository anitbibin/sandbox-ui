#!groovy
pipeline {
  agent none
  stages {
    stage('Docker Build') {
      agent { dockerfile true }
      steps {
        echo "deploying ... "
        sh "docker build -t anitbibin/sandbox-ui -f Dockerfile ."
      }
    }
  }
}
