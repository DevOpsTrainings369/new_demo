pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bash 'ls -lrt '
      }
    }
    stage('Test Firefox') {
      parallel {
        stage('Test Firefox') {
          steps {
            bash 'ls -lrt'
          }
        }
        stage('Test Chrome') {
          steps {
            bash 'ls -lrt'
          }
        }
        stage('Test Edge') {
          steps {
            bash 'ls -lrt'
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        bash 'ls -lrt'
      }
    }
  }
}
