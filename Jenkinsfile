pipeline {
    agent { docker { image 'maven:eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
