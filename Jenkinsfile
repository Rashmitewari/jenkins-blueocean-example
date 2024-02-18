pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
Date





                     '''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test message'
          }
        }

        stage('test par') {
          steps {
            echo 'test par'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

    stage('time') {
      steps {
        sleep 13
      }
    }

  }
}