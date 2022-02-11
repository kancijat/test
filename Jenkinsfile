pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
        sh 'ls -la'
        sh 'java -version'
      }
    }
    stage('Display') {
      steps {
        sh 'echo Displaying message'
      }
    }
  }
}
