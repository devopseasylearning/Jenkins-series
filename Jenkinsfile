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
            when {
                expression {
                env.APP == 'Canary' || env.APP == 'Ansible'

                }
            }
            steps {
                echo 'Hello World'
            }
        }


        stage('test') {
            when {
                expression {
                    env.REGISTRY == 'NEXUS'
                }
            }
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
