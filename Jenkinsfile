pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh '/home/juppe_agon/maven3/bin/mvn clean install'
            }
        }
        stage('Test') { 
            steps {
                sh '/home/juppe_agon/maven3/bin/mvn test' 
            }
        }
       
        }
    }

