pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello Build'
          }
        }

        stage('Build 2') {
          steps {
            sh 'dzndcizcn'
          }
        }

      }
    }

    stage('Test ') {
      steps {
        echo 'Hello Test'
      }
    }

    stage('Deployement') {
      steps {
        echo 'Run Deployemt ....'
      }
    }

  }
}