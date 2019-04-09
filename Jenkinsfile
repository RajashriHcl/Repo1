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
        echo '"\''
      }
    }
    stage('Report') {
      environment {
        CI = 'true'
      }
      steps {
        echo '""'
        sh './jenkins/scripts/test.sh'
      }
    }
  }
}