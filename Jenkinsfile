pipeline {
  agent {
    node {
      label 'slave'
    }
    
  }
  stages {
    stage('Prompt') {
      steps {
        input(message: 'Test Input', id: 'Input', ok: 'Input', submitter: 'Test', submitterParameter: 'Test')
      }
    }
    stage('') {
      steps {
        echo 'Test Succeeded'
      }
    }
  }
}