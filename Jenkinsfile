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
                echo $NAME
                APP=Canary
                echo $APP
                '''
            }
        }

        stage('test') {
            steps {
                sh '''
                echo $NAME
                echo $APP
                '''
            }
        }

        stage('verify') {
            steps {
                sh '''
                echo $NAME
                
                '''
            }
        }

        stage('deploy') {
            steps {
                sh '''
                echo $NAME
                
                '''
            }
        }

    }
}
