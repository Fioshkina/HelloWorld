pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                withMaven(maven : 'maven:3.5.4') {
                    sh 'mvn --version'
                }
            }
        }
    }
}

