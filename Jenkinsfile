pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        checkout scm
      }
    }
    stage( 'Test Webhook') {
      steps {
        echo "Webhook triggered successfully !"
        sh "cat index.txt"
      }
    }
  }
}
