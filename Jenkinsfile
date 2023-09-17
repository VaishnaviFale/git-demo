pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                echo 'JAVA VERSION - '
                sh 'java -version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
         stage('SAST') {
            steps {
                echo 'SAST Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}


