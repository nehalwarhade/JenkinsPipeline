pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build is success !!!!!'
          }
        }

        stage('Test') {
          steps {
            echo 'Test is success !!!'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy is success !!!'
      }
    }

  }
}