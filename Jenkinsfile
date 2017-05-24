pipeline {
  agent {
    node {
      label 'slave'
    }
    
  }
  stages {
    stage('Prompt') {
      steps {
        input(message: 'Test Input', id: 'Input', ok: 'true')
      }
    }
    stage('error') {
      steps {
        echo 'Test Succeeded'
      }
    }
  }
}