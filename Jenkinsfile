pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Used using blueocean'
      }
    }

    stage('new stage') {
      steps {
        sh '''df -h
hostname
ifconfig'''
      }
    }

  }
}