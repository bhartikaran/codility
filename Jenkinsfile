pipeline {
  agent any
  stages {
    stage('version of python') {
      steps {
        bat 'python --version'
      }
    }
    stage ('running script') {
      steps {
        bat 'python L3_FrogJmp.py'
      }
    }
}
}
