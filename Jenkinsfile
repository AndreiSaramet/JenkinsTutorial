/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    environment {
        PATH = "/usr/local/bin:$PATH"
    }
    stages {
        stage('build') {
            steps {
                sh 'python3.12 --version'
            }
        }
    }
}
