pipeline {
  agent any
  stages {
    stage('Node Update') {
      steps {
        sh 'npm -v'
        sh 'npm install'
        sh 'npm prune'
      }
    }
    stage('Unit Testing') {
      steps {
        sh 'npm run jenk-unit-test'
      }
    }
  }
}