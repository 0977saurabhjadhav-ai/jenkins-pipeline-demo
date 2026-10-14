```groovy
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out GitHub repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'echo Build Successful!'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Tests Passed!'
            }
        }

        stage('Complete') {
            steps {
                echo 'GitHub Jenkins Pipeline completed successfully!'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }

        failure {
            echo 'Pipeline failed. Check Console Output.'
        }
    }
}
```
