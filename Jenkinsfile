pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code Git se aa gaya!'
                sh 'ls -la'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'date'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }

    post {
        success { echo 'all good' }
        failure { echo 'Fail ❌' }
    }
}
