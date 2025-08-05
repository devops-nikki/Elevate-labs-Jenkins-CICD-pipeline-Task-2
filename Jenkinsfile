pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'ls -l' // lists files like index.html
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // You can skip or add basic validation if needed
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the web page...'
                // For demo purpose, just show content
                sh 'cat index.html'
            }
        }
    }
}
