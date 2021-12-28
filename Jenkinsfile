pipeline {
  agent any
  stages {
    stage('t1') {
      parallel {
        stage('t1') {
          steps {
            sh 'echo 1'
          }
        }

        stage('test2') {
          steps {
            sh 'echo 2'
            sh 'echo 2'
          }
        }

      }
    }

    stage('t3') {
      steps {
        sh 'echo 3'
      }
    }

  }
}