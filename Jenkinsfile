pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm --version' 
                mocha MyBooking/MyBooking.js 
            }
        }
    }
}
