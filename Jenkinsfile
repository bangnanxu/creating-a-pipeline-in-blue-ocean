pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6-alpine'
    }

  }
  stages {
    stage('') {
      steps {
        build 'npm install'
        sh 'npm install'
      }
    }
  }
}