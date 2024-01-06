pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                echo 'Starting the pipeline...'
                // Initialization steps go here
            }
        }

        stage('Build') {
            steps {
                sh '''
                echo "abc"
                '''
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Test commands go here
                // Example: sh './run-tests.sh'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging environment...'
                // Deployment commands for staging go here
                // Example: sh './deploy-staging.sh'
            }
        }

        stage('Production Deployment') {
            steps {
                echo 'Deploying to production...'
                // Deployment commands for production go here
                // Example: sh './deploy-prod.sh'
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution is finished!'
        }
    }
}
