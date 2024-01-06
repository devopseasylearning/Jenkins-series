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
                echo $BUILD_NUMBER
                APP=Canary
                echo $APP
                '''
            }
        }

        stage('test') {
            steps {
                sh '''
                echo $BUILD_NUMBER
                '''
            }
        }

        stage('verify') {
            steps {
                sh '''
                echo $BUILD_NUMBER
                
                '''
            }
        }

        stage('deploy') {
            steps {
                sh '''
                echo $BUILD_NUMBER
                
                '''
            }
        }

    }
}
