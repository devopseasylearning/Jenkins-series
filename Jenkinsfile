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
            steps {
                echo 'Hello World'
            }
        }

        stage('deploy') {
            steps {
                echo 'Hello World'
            }
        }

    }





}
