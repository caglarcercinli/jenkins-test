pipeline {
  agent any
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/caglarcercinli/jenkins-test', branch: 'master')
      }
    }

    stage('Log') {
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

    stage('Push to Dockerhub') {
      steps {
        sh 'echo \'push to dockerhub\''
      }
    }

  }
}