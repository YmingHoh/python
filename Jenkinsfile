pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python3 python2.py'
      }
    }
    stage('deliver') {
      steps {
        echo 'done uggla'
      }
    }
  }
}