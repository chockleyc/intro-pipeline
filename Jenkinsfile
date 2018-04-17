pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        echo '\'Hello ${MY_NAME}!\''
      }
    }
  }
  environment {
    MY_NAME = 'Chris'
  }
}