pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                echo 'Pulling code...'
                sh 'ls -l'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'cat hello.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Tests passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo "Deployment complete!"'
            }
        }
    }
}
