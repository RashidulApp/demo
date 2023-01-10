pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/RashidulApp/demo', branch: 'simple_state')
      }
    }

    stage('') {
      steps {
        sh '''npm install
npm run dev'''
      }
    }

  }
}