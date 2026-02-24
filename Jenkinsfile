pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }

      post {
        success {
            sh 'echo "build successful"'
        }
        failure {
            sh 'echo "build failed"'
        }
    }
}
