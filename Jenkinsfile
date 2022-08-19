pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build Message'
          }
        }

        stage('Parallel Build') {
          steps {
            echo 'Parallel Build Message'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test Message'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Message'
      }
    }

  }
}