pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/mokshmalik5757/curriculum-app.git', branch: 'dev')
      }
    }

    stage('Logs') {
      steps {
        sh 'ls -la'
      }
    }

  }
  tools {
    nodejs 'nodejs'
  }
}
