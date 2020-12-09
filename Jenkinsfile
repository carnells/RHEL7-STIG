pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:centos:latest'
    }

  }
  stages {
    stage('Insitialize /Print Message') {
      steps {
        echo 'This is just a test '
      }
    }

  }
}