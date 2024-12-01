pipeline {
    agent { docker { 
                image 'maven:amazoncorretto-17-windowsservercore' 
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
