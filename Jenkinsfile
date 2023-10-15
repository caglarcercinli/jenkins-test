pipeline {
  agent any
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/caglarcercinli/jenkins-test', branch: 'master')
      }
    }

    stage('Error') {
      steps {
        sh 'ls -la'
      }
    }

    stage('Build') {
      steps {
        sh 'echo \'build\''
      }
    }

    stage('login to Dockerhub') {
      steps {
        sh '''echo \'dockerhub login\'
'''
      }
    }

  }
}