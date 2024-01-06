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
               echo NODE_NAME
               echo ${BUILD_NUMBER}
               echo ${NODE_LABELS}
               echo ${WORKSPACE}
               echo ${JENKINS_HOME}
               echo ${JENKINS_URL}
                '''
            }
        }

        stage('test') {
            steps {
                sh '''
               echo NODE_NAME
               echo ${BUILD_NUMBER}
               echo ${NODE_LABELS}
               echo ${WORKSPACE}
               echo ${JENKINS_HOME}
               echo ${JENKINS_URL}
                '''
            }
        }

        stage('verify') {
            steps {
                sh '''
               echo NODE_NAME
               echo ${BUILD_NUMBER}
               echo ${NODE_LABELS}
               echo ${WORKSPACE}
               echo ${JENKINS_HOME}
               echo ${JENKINS_URL}
                
                '''
            }
        }

        stage('deploy') {
            steps {
                sh '''
               echo NODE_NAME
               echo ${BUILD_NUMBER}
               echo ${NODE_LABELS}
               echo ${WORKSPACE}
               echo ${JENKINS_HOME}
               echo ${JENKINS_URL}
                
                '''
            }
        }

    }
}
