pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World ${MY_NAME}!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}