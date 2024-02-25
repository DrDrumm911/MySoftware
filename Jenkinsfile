pipeline {
    agent any

    triggers {
        cron('H/30 * * * *') // Poll GitHub every 30 minutes
    }

    stages {
        stage('Checkout') {
            steps {
                // Checkout your repository from GitHub
                git 'https://github.com/yourusername/yourrepository.git'
            }
        }

        stage('Build') {
            steps {
                // Your build steps here
                sh 'echo "Building..."'
            }
        }

        // Add more stages as needed
    }
}
