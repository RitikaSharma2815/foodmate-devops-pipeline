pipeline {
    agent any

    stages {
        stage('Test Failure') {
            steps {
                echo 'This should fail...'
                sh 'exit 1'
            }
        }
    }
}



