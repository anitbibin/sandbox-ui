pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('master') {
      steps {
        sh 'docker build -t anitbibin/sandbox-ui .'
      }
    }
  }
}
