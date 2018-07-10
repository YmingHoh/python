pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python3 class.py'
      }
    }
    stage('deliver') {
      steps {
        echo 'done done done'
      }
    }
  }
}