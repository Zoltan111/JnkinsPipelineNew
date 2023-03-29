pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building the Application'
            echo 'msg2'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing the Application'
          }
        }

      }
    }

    stage('Deployment') {
      steps {
        echo 'DEploying the Application'
      }
    }

  }
}