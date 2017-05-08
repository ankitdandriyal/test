pipeline {
  agent any
  stages {
    stage('Job1') {
      steps {
        sh 'echo "JOB1"'
      }
    }
    stage('Job2') {
      steps {
        sh 'echo "Hello"'
      }
    }
  }
  environment {
    DEV = '1'
  }
}