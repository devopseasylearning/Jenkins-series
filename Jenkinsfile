pipeline {

    agent any
    parameters {
      choice choices: ['DEV', 'QA', 'SECURITY', 'DEVOPS', 'PRE-PROD', 'PROD'],
       name: 'ENVIRONMENT',
       description: 'Select an environment'
        
      string defaultValue: 'Canary', 
      name: 'APP',
      description: 'Enter the application name'
      
      choice choices: ['ECR', 'DOCKERHUB', 'NEXUS'], 
      name: 'REGISTRY',
      description: 'Select the registry where you want to push your image'
      
       
    }

    stages {

        
        stage('build') {
            steps {
                sh '''
               echo  $BRANCH_NAME
               echo $CHANGE_AUTHOR
               echo $BUILD_NUMBER
                '''
            }
        }





    }





}
