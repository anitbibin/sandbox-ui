#!groovy
node('docker') {
    stage 'Checkout'
        checkout scm
    stage 'Build & UnitTest'
        sh "docker build -t anitbibin/sandbox-ui -f Dockerfile ."
}