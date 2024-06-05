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
        bat 'python L4_MaxCounters.py'
        bat 'python L4_PermCheck.py'
        bat 'python L5_PassingCars.py'
      }
    }
}
}
