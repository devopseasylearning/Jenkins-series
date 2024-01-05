





pipeline {
    agent any

     stages {

        stage('Build') {
           steps {
             sh '''
             sleep 10
              '''
             } 


          }


        stage('test') {
           steps {
             sh '''
             sleep 10
              '''
             } 


          }


        stage('push to nexus') {
           steps {
             sh '''
             sleep 10
              '''
             } 


          }

        stage('push to dockerhub') {
           steps {
             sh '''
             sleep 10
              '''
             } 


          }


          

     }

    post {
        success {
            // Actions to perform on success
            slackSend(channel: 'development-alerts', message: "SUCCESS: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]' (${env.BUILD_URL})")
        }
        failure {
            // Actions to perform on failure
            slackSend(channel: 'development-alerts', message: "FAILURE: Job '${env.JOB_NAME} [${env.BUILD_NUMBER}]' (${env.BUILD_URL})")
        }
        // Additional conditions (like 'always', 'unstable') if needed
    }


}





 
