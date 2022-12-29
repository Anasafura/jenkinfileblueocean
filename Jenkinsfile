pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''ls date   pwd cat

'''
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