pipeline {
  agent {
    dockerfile {
      filename 'docker pull centos:8.3.2011'
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