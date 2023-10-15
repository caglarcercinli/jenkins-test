pipeline {
  agent any
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/caglarcercinli/jenkins-test', branch: 'master')
      }
    }

    stage('Error') {
      parallel {
        stage('Error') {
          steps {
            sh 'ls -la'
          }
        }

        stage('Front-end unit test') {
          steps {
            sh 'npm -v'
          }
        }

      }
    }

  }
}