pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo BUILD Stage completeed'
            }
        }
        stage('Test') {
            steps {
                sh 'echo TEST Stage completeed'
            }
        }
        stage('Deliver') {
            steps {
                sh 'echo DELIVER Stage completeed'
            }
        }
    }
}
