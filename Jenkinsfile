pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('dev') {
      steps {
        sh 'docker build -t anitbibin/sandbox-ui .'
      }
    }
  }
}
