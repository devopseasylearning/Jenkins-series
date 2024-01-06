pipeline {
    agent any
    environment {
      NAME = "user"
      COUNTRY = "Mexico"
    }

    stages {

        stage('build') {
            steps {
                sh '''
                echo $BRANCH_NAME
                APP=Canary
                echo $APP
                '''
            }
        }

        stage('test') {
            steps {
                sh '''
                echo $BRANCH_NAME
                '''
            }
        }

        stage('verify') {
            steps {
                sh '''
                echo $BRANCH_NAME
                
                '''
            }
        }

        stage('deploy') {
            steps {
                sh '''
                echo $BRANCH_NAME
                
                '''
            }
        }

    }
}
