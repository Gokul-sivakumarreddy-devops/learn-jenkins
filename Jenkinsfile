pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }

        stages {
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }

        stages {
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}