pipeline {
  agent any
  stages {
    stage('Starting') {
      steps {
        parallel(
          "Starting": {
            echo 'Starting Build'
            
          },
          "": {
            echo 'Paralleling man ohhh'
            
          }
        )
      }
    }
    stage('Build') {
      steps {
        echo 'Hello from build'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing Testing 123'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy something'
      }
    }
  }
}