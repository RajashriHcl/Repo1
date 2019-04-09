pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo '"initial state"'
      }
    }
    stage('Build') {
      steps {
        bat '"hii"'
      }
    }
    stage('Report') {
      steps {
        junit '""'
      }
    }
  }
}