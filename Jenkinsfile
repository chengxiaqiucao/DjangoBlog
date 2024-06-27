pipeline {
  agent any
  stages {
    stage('testing') {
      parallel {
        stage('testing') {
          steps {
            sh 'echo "this is a test"'
          }
        }

        stage('OK') {
          steps {
            sleep 3
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'building............'
      }
    }

  }
}