pipeline {
  agent any
  stages {
    stage('Starting') {
      parallel {
        stage('Starting') {
          steps {
            echo 'Starting Build'
          }
        }
        stage('Parallel Start') {
          steps {
            echo 'Paralleling man ohhh'
          }
        }
      }
    }
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello from build'
          }
        }
        stage('parallel Build') {
          steps {
            echo 'Parallel build ...'
          }
        }
      }
    }
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Testing Testing 123'
          }
        }
        stage('Parallel Test ...') {
          steps {
            echo 'parallel test'
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy something'
      }
    }
  }
  environment {
    aa = 'aa'
  }
}