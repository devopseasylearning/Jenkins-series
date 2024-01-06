pipeline {

    agent any
     parameters {
       booleanParam description: 'verify if the config file exist', name: 'true'
       choice choices: ['NIGERIA', 'CAMEROON', 'USA', 'GHANA', 'MEXICO'],
        description: 'Select your country ',
        name: 'COUNTRY'
       string defaultValue: 'eric',
        description: 'enter your name', 
        name: 'NAME'
       file description: 'upload the config file to here',
        name: ''
     }
    stages {

        stage('test') {
            steps {
               sh '''
               echo "my name is $NAME I am from $COUNTRY"
               '''
            }
        }


    }


}
