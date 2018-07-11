pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python4 class.py'
      }
    }
    stage('deliver') {
      steps {
        echo 'done rosen'
      }
    }
  }
}