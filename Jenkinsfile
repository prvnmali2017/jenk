pipeline  {
    agent any
    stages {
        stage('Build') {
            steps {
 withEnv(['HOME=$WORKSPACE']) {
            docker.image('node:6.6.0').inside {
            sh 'npm install'
              mocha MyBooking/MyBooking.js
            }
            }
          }
        }
    }
}
