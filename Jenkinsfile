pipeline {
  agent any
  stages {
    stage('master') {
      parallel {
        stage('master') {
          steps {
            sh 'echo \'hello from Pipeline\''
          }
        }

        stage('feature1') {
          steps {
            sh 'echo \'hello from Pipeline\''
          }
        }

      }
    }

  }
}