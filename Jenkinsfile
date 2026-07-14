pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out source code...'
                // git 'https://github.com/your-username/your-repository.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'echo Build Successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo All Tests Passed'
            }
        }

        stage('Package') {
            steps {
                echo 'Packaging the application...'
                sh 'echo Package Created'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                sh 'echo Deployment Successful'
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution complete.'
        }

        success {
            echo 'Pipeline completed successfully!'
        }

        failure {
            echo 'Pipeline failed.'
        }
    }
}


d24bde5f09d141b39e8a463ab8457ccf
