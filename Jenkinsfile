pipeline {
  agent {
    node {
      label 'mynode'
    }

  }
  stages {
    stage('Checkout') {
      steps {
        echo 'Hello from checkout'
      }
    }
  }
  environment {
    Dev = '1'
    test = '1'
  }
}