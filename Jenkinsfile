pipeline {
    agent {
        docker {
            image 'maven:latest'
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
