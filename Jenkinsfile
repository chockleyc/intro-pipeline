pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Chris'
    TEST_USER = credentials('test-user')
  }
}