pipeline {
    agent any 
    tools {
    maven 'M3'
    } 
    stages {
        stage('...clone...') { 
            steps {
                sh "mvn clean" 
            }
        }
        stage('test') { 
            steps {
                sh "mvn test"
            }
        }
        stage('deploy') { 
            steps {
                sh "mvn package" 
           }
        }
    }
}
