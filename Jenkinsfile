pipeline {
    agent any

    stages {

        stage('test') {
            steps {
                sh '''
                ls -l 
                '''
            }
        }

        stage('build') {
	     agent {
            docker {
              image 'node:latest'
            }
           }
            steps {
                echo 'Hello World'
            }
        }

        stage('deploy') {
	     agent {
            docker {
              image 'alpine:latest'
            }
           }
            steps {
                echo 'Hello World'
            }
        }

    }





}
