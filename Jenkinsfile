pipeline {
    agent any

    tools {
        nodejs "node18"
    }

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                bat 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application Deployed Successfully'
            }
        }
    }
}