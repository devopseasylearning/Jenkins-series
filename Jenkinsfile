pipeline{
   agent any
   options {
     buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '5', numToKeepStr: '5')
     disableConcurrentBuilds()
     timestamps
     timeout(time: 2, unit: 'HOURS')
   }
   
   environment {
     APP = "canary"
     USER = "john"
   }
   
   stages {
     stage('unit-test') {
       steps {
         sh '''
               uname -r
               ls -l 
               java -version
               echo $APP
               echo $USER
             '''
       }
     }
   
     stage('build') {
       steps {
         sh '''
               uname -r
               ls -l 
               java -version
               echo $APP
               echo $USER
             '''
       }
     }
   
     stage('push ') {
       steps {
         sh '''
               uname -r
               ls -l 
               java -version
               echo $APP
               echo $USER
             '''
       }
     }
   
     stage('deploy') {
       steps {
         sh '''
               uname -r
               ls -l 
               java -version
               echo $APP
               echo $USER
             '''
       }
     }
   
    // post {
    //   success {
    //     slackSend channel: 'development-alerts', message: 'the build was really a success'
    //   }

    //   failure {
    //     slackSend channel: 'development-alerts', message: 'the build was NOT  a success'
    //   }

    //   unstable {
    //     slackSend channel: 'development-alerts', message: 'the build was not stable'
    //   }
    // }


   }
   










}
