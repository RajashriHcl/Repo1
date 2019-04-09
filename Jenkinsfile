pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Initialize') {
      steps {
        echo '"initial state"'
      }
    }
    stage('Build') {
      steps {
        bat 'echo"hii"'
      }
    }
    stage('Report') {
      steps {
        junit '""'
      }
    }
  }
}