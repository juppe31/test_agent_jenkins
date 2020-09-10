pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               sudo sh '/home/juppe_agon/maven3/bin/mvn clean install'
            }
        }
        stage('Test') { 
            steps {
                sudo sh '/home/juppe_agon/maven3/bin/mvn test' 
            }
        }
       
        }
    }

