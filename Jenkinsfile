pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build started successfully!'
                bat 'echo Hello from Jenkins!'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage executed successfully!'
            }
        }
    }

    post {
        success {
            echo 'PIPELINE SUCCESS!'
        }
        failure {
            echo 'PIPELINE FAILED!'
        }
    }
}
