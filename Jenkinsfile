pipeline {
  agent any
  stages {
    stage('Starting') {
      steps {
        parallel(
          "Starting": {
            echo 'Starting Build'
            
          },
          "Parallel Start": {
            echo 'Paralleling man ohhh'
            
          }
        )
      }
    }
    stage('Build') {
      steps {
        parallel(
          "Build": {
            echo 'Hello from build'
            
          },
          "parallel Build": {
            echo 'Parallel build ...'
            
          }
        )
      }
    }
    stage('Test') {
      steps {
        parallel(
          "Test": {
            echo 'Testing Testing 123'
            
          },
          "Parallel Test ...": {
            echo 'parallel test'
            
          }
        )
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy something'
      }
    }
  }
}