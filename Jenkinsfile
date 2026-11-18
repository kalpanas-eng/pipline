
pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the Application'
                bat 'echo Application Build Successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the Application'
                bat 'echo Testing Successful'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the Application'
                bat 'echo Deployment Successful'
            }
        }
    }

    post {
        success {
            echo 'Pipeline Executed Successfully!'
        }

        failure {
            echo 'Pipeline Failed!'
        }
    }
}
