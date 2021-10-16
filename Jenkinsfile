pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'This is the $BUILD_NUMBER of job $DEMO'
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}