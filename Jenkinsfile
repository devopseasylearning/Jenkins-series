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
               echo "NODE_NAME"
               echo "NODE_LABELS"
               echo "WORKSPACE"
               echo "JENKINS_HOME"
               echo "JENKINS_URL"
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
