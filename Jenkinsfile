pipeline  {
    agent any
    stages {
        stage('Build') {
            steps {
 withEnv(['HOME=$WORKSPACE']) {
              sh 'npm install'
              mocha MyBooking/MyBooking.js
            }
          }
        }
    }
}
