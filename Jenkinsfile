/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    environment {
        PATH = "/Library/Frameworks/Python.framework/Versions/3.12/bin/python3.12:$PATH"
    }
    stages {
        stage('build') {
            steps {
                sh 'echo $PATH'
                sh 'python3.12 --version'
            }
        }
    }
}
