pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        bat(script: '1.py', encoding: 'utf-8', label: 'test1', returnStatus: true, returnStdout: true)
      }
    }

  }
}