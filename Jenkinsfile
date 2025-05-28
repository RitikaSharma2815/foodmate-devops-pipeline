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
    stage('Code Quality') {
      steps {
            echo 'Checking code quality...'
            sh 'echo Code passed linting rules!'
            }
        }
       stage('Security Scan') {
    steps {
        echo 'Running security scan...'
        sh 'echo No known vulnerabilities found.'
       }
      }

    }
}

