





pipeline {
    agent any

     stages {

        stage('Build') {
           steps {
             sh '''
             ls
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





 

