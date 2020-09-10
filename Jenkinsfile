pipeline {
    agent any
    stages {
        stage('Build') {
            agent any
            steps {
                sh 'sudo /home/juppe_agon/maven3/bin/mvn clean install'
            }
        }
        stage('Test') { 
            agent any
            steps {
                sh 'sudo /home/juppe_agon/maven3/bin/mvn test' 
            }
        }
       
        }
    }

