pipeline {
  agent any
  stages {
    stage('Change code') {
      steps {
        git(url: 'https://github.com/ghassan1212/Open-Google', branch: 'dev', credentialsId: 'Change code')
      }
    }

  }
}