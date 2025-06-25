pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '🔧 Building the code...'
                bat 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo '✅ Running tests...'
                // Add test commands here if any
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying application...'
                // Simulate deploy
            }
        }
    }
}
