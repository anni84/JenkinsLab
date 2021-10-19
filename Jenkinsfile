pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "Hello $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}