pipeline {
  agent {
    node {
      label 'jenkins-docker-slave'
    }

  }
  stages {
    stage('checkout-code') {
      steps {
        sh 'echo "hello world"'
      }
    }

    stage('install node v10') {
      steps {
        sh 'echo "hello2"'
      }
    }

    stage('build node package') {
      steps {
        sh 'echo "hello3"'
      }
    }

  }
}