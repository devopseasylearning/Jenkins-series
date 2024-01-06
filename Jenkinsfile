pipeline {
    agent {
        docker {
            image 'maven:3.8.7-openjdk-18-slim'
        }
    }
    

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
