pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bash 'echo "Building" '
      }
    }
    stage('Test Firefox') {
      parallel {
        stage('Test Firefox') {
          steps {
            bash 'echo \'Testing Firefox\''
          }
        }
        stage('Test Chrome') {
          steps {
            bash 'echo \'Testing Chrome\''
          }
        }
        stage('Test Edge') {
          steps {
            bash 'echo \'Testing Edge\''
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        bash 'echo "Deploy"'
      }
    }
  }
}
