pipeline {
    agent { docker { 
                image 'maven:3.9.9-eclipse-temurin-21-alpine' 
                args '-v C:/Users/GH29052/.jenkins/workspace/My-Pipeline_main:/workspace' 
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
