pipeline {
  agent any
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/caglarcercinli/jenkins-test', branch: 'master')
      }
    }

  }
}