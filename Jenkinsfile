pipeline {
  agent any
  stages {
    stage('Step 1') {
      steps {
        echo 'Starting Build Process'
      }
    }

    stage('Packaging') {
      steps {
        withGradle()
      }
    }

    stage('Success') {
      steps {
        echo 'Success'
      }
    }

  }
}