pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/pedrozamuner/jenkins-test-demo.git', branch: 'main')
      }
    }

    stage('List files') {
      steps {
        sh 'ls -la'
      }
    }

  }
}