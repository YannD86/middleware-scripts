pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build'
                sleep 10
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
                sleep 10
            }
        }
        stage('Docker') {
            steps {
                echo 'Image'
            }
        }
    }
}
