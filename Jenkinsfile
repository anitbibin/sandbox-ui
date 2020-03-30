pipeline {
  agent none
  stages {
    stage("Docker build") {
      agent { dockerfile true }
      steps {
        sh "docker build -t anitbibin/sandbox-ui ."
      }
    }
  }
}
