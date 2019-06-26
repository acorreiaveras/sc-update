pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/acorreiaveras/jenkins-automation', branch: 'master', changelog: true)
      }
    }
    stage('Update') {
      steps {
        sh 'echo build triggered'
      }
    }
  }
}