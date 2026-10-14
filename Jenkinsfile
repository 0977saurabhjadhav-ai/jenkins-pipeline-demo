pipeline {
agent any

```
stages {
    stage('Checkout') {
        steps {
            echo 'GitHub repository checkout successful!'
        }
    }

    stage('Build') {
        steps {
            echo 'Building project...'
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
            echo 'Jenkins Pipeline completed successfully!'
        }
    }
}

post {
    success {
        echo 'Pipeline executed successfully!'
    }

    failure {
        echo 'Pipeline failed!'
    }
}
```

}
