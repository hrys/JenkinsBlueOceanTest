pipeline {
  agent any
  stages {
    stage('Test01') {
      steps {
        echo 'Test01'
      }
    }

    stage('Test02') {
      parallel {
        stage('Test02_01') {
          steps {
            echo 'Test02_01'
          }
        }

        stage('Test02_02') {
          steps {
            echo 'Test02_02'
          }
        }

      }
    }

    stage('Test03') {
      steps {
        echo 'Test03'
      }
    }

  }
}