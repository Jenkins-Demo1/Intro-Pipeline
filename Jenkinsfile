pipeline {
  agent {
    label 'jdk9'
  }
     environment {
      MY_NAME = 'Mary'
   }stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World ${MY_NAME}!'
        sh 'java -version'
      }
    }
  }
}
