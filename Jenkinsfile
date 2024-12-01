pipeline {
    agent { docker { 
                image '3.9.9-eclipse-temurin-21-windowsservercore' 
                } 
          }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
