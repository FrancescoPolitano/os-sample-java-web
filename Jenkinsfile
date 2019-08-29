pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo mvn --version'
                sh 'mvn clean install'
            }
        }
    }
} 
