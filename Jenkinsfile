pipeline {
  agent any
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/caglarcercinli/jenkins-test', branch: 'master')
      }
    }

    stage('Adds a log') {
      steps {
        sh 'ls -la'
      }
    }

  }
}