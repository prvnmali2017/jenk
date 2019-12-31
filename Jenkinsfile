node('docker') {
  stage('Checkout') {
    checkout scm
  }

  stage('Build') {
        withEnv(['HOME=$WORKSPACE']) {
          docker.image('node:6.6.0').inside {
            sh 'npm install'
          }
        }
  }
}
