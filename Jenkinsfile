pipeline {
  agent any
  stages {
    stage('Install modules') {
      parallel {
        stage('Install modules') {
          steps {
            sh 'yarn install'
          }
        }
        stage('Composer') {
          steps {
            sh 'composer install'
          }
        }
      }
    }
  }
}