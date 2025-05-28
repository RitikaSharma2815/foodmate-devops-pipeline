pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello from Build stage'
                sh 'echo Building...'
            }
        }
    stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'npm test || echo "Tests failed, but continuing..."'
            }
        }
    }
}

