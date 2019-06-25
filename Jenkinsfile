pipeline {
    agent any
    environment {
        PATH = "C:\DevOps\apache-maven-3.6.0\bin;%PATH%"
    }
    stages {
        stage('Build') { 
            steps {
                bat 'set'
                bat 'mvn clean package'
            }
        }
    }
}
