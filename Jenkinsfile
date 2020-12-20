pipeline {
    agent any
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
