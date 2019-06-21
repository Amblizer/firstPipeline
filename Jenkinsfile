// Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Initialize'){
            env.PATH = "${tool 'dockerTest'}/bin:${env.PATH}"
        }
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}