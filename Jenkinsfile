pipeline {
    
    stages {
        stage('Build') { 
            steps {
                sh 'sudo /home/juppe_agon/maven3/bin/mvn clean install'
            }
        }
        stage('Test') { 
            steps {
                sh 'sudo /home/juppe_agon/maven3/bin/mvn test' 
            }
        }
       
        }
    }

