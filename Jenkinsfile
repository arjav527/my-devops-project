pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/username/jenkins-docker.git' // Replace 'username' with your GitHub username
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add your build commands here, e.g., sh 'make' or sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here, e.g., sh 'npm test'
            }
        }
    }
}