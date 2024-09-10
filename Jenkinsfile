pipeline {
  agent any
  stages {
    stage('Log') {
      steps {
        sh 'ls -la'
      }
    }
    stage('Build') {
      steps {
        sh 'docker build -f curriculum-front/Dockerfile -t anhquan99/curriculum-front:latest .'
      }
    }
  }
}