pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('CB Jenkins Stage One') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
}