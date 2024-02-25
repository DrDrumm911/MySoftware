pipeline {
    agent any

    triggers {
        cron('H/30 * * * *') // Poll GitHub every 30 minutes
    }

    stages {
        stage('Checkout') {
            steps {
                // Checkout your repository from GitHub
                git 'https://github.com/DrDrumm911/MySoftware.git'
            }
        }

        stage('Build') {
            steps {
                // Your build steps here
            }
        }

        // Additional stages as needed
    }
}
