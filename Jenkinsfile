pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''python3
python1.py'''
      }
    }
    stage('deliver') {
      steps {
        echo 'done rosen'
      }
    }
  }
}