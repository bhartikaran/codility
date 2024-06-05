pipeline {
  agent any
  stages {
    stage('version of python') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('Running Script') {
      steps {
        sh 'python3 count_not_divisible.py'
      }
    }
  }
}
