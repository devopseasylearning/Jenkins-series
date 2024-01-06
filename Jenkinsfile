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
                echo " I am from $COUNTRY"
                '''
            }
        }

        stage('test') {
            steps {
                sh '''
                echo $NAME
                echo " I am from $COUNTRY"
                '''
            }
        }

        stage('verify') {
            steps {
                sh '''
                echo $NAME
                echo " I am from $COUNTRY"
                '''
            }
        }

        stage('deploy') {
            steps {
                sh '''
                echo $NAME
                echo " I am from $COUNTRY"
                '''
            }
        }

    }
}
