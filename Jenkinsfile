#!groovy
pipeline {
  environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"
  agent { docker 'python:3.5.1' }
  stages {
    stage('build') {
      steps {
        sh 'pip --version'
        sh 'python --version'
      }
    }
  }
}
