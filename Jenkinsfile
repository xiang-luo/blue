pipeline {
  agent {
    node {
      label 'local-agent1'
    }

  }
  stages {
    stage('1') {
      steps {
        bat(script: '1.py', encoding: 'utf-8', label: 'test1', returnStatus: true, returnStdout: true)
      }
    }

    stage('2') {
      steps {
        sh 'echo "Hello world2"'
      }
    }

  }
}