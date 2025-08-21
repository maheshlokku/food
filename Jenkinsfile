pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout code from GitHub
                git branch: 'master', url: 'https://github.com/maheshlokku/food.git'
            }
        }
        stage('Build') {
            steps {
                echo "No build needed for HTML project"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying static website files..."
                // Example: Copy to a web server directory
                // sh 'cp -r * /var/www/html/'
            }
        }
    }
}
