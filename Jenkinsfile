pipeline {
    agent any
    tools {
        maven 'maven:3.5.4'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

