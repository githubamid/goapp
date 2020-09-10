pipeline {
  agent { 
    label 'goleng' 
    }
  stages {
    stage('Build') {
      steps {
        sh "go version"
        sh "go build main.go"
      }
    }
    stage('Test') {
      steps {
        sh "go test"
      }
    }
  }
}
