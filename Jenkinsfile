pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "hellow world"'
      }
    }
    stage('test') {
      steps {
        error 'may err'
      }
    }
  }
}