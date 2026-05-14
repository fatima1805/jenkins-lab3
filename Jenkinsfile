pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'ls'
                sh 'pwd'
                sh 'touch build-output.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'ls'
                sh 'pwd'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'mv build-output.txt deployed-output.txt'
                sh 'ls'
            }
        }
    }
}
