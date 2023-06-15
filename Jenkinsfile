pipeline {
    agent { label 'slave1' } 
    stages {
        stage('checkout') {
            steps {
                sh 'echo checkout step'
            }
        }
        stage('testing1') {
            steps {
                sh 'echo testing step'
            }
        }
        stage('testing2') {
            steps {
                sh 'echo testing2 step'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo deploy step'
            }
        }
    }
    }
