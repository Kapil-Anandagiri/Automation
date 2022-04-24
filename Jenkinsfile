pipeline {
  agent any
  stages {
    stage('CI') {
      steps {
        echo 'CI Jenkins Started'
      }
    }

    stage('SIT1') {
      steps {
        echo 'SIT Jenkins Initated'
      }
    }

    stage('PROD') {
      steps {
        echo 'Prod Jenkins Initiated'
      }
    }

  }
  environment {
    SIT = 'Https:\\\\localhost\\2020'
  }
}