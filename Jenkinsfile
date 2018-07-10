pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python3 celcius.py'
      }
    }
    stage('deliver') {
      steps {
        echo 'done done'
      }
    }
  }
}