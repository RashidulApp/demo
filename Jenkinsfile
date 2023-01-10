pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/RashidulApp/demo', branch: 'simple_state')
      }
    }

    stage('error') {
      steps {
        sh 'npm run dev'
      }
    }

  }
}