pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python4.py'
      }
    }
    stage('deliver') {
      steps {
        echo 'done rosen'
      }
    }
  }
}