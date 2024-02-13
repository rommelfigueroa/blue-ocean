pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Test'
          }
        }

        stage('Parallel') {
          steps {
            echo 'Parallel'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Build'
      }
    }

    stage('Clean Up') {
      steps {
        echo 'Clean Up'
      }
    }

  }
}