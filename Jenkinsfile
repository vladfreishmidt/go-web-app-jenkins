pipeline {
  agent any
  tools {
    go 'go-1.25.3'
  }

  environment {
    GO111MODULE='on'
  }

  stages {
    stage('Test') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}