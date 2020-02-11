pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'Hello'
          }
        }

        stage('Test') {
          steps {
            sh '''acho "Hello"
'''
          }
        }

      }
    }

    stage('Stage2') {
      steps {
        echo 'stage2'
      }
    }

    stage('Stage3') {
      steps {
        echo 'stage3'
      }
    }

  }
}