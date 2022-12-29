pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'ls'
      }
    }

    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'Hello Build'
          }
        }

        stage('bluidp') {
          steps {
            echo 'parel'
          }
        }

      }
    }

    stage('deplo') {
      steps {
        echo 'deploy'
      }
    }

  }
}