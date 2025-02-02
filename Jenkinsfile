/* Requires the Docker Pipeline plugin */
pipeline {
    environment {
        PATH = "/usr/local/bin:$PATH"
    }
    agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python3.12 --version'
            }
        }
    }
}
