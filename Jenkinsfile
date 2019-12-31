pipeline {
    agent {  }    
    stages {
        stage('build') {
            steps {
              sh 'npm --version'
	      mocha MyBooking/MyBooking.js
            }
        }
    }
}
