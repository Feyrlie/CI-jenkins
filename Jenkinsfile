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
        withGradle() {
          echo 'Success'
        }

      }
    }

    stage('Success') {
      steps {
        echo 'Success'
      }
    }

  }
}