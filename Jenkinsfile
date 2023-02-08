pipeline {
    agent any 
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
