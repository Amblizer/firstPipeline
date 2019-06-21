// Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Initialize'){
            steps{
                def dockerHome = tool 'dockerTest'
                env.PATH = "${dockerHome}/bin:${env.PATH}"
            }
        }
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}