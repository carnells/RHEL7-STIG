pipeline {
  agent {
    docker {
      image 'node:6-alphine'
      args '-p 3000:3000'
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