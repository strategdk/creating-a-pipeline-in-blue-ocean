pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:000'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}