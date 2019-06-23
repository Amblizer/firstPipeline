// Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
    stage('Initialize'){
            def dockerHome = tool 'myDocker'
            env.PATH = "${dockerHome}/bin:${env.PATH}"
        }
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}