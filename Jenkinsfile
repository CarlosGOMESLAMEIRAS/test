pipeline {
  agent any
  stages {
    stage('stageBranch2Test1') {
      parallel {
        stage('stageBranch2Test1') {
          steps {
            echo 'Hola '
          }
        }
        stage('error') {
          steps {
            waitUntil() {
              sleep 10
            }
            
          }
        }
      }
    }
    stage('endStageTest1') {
      steps {
        echo 'Fin des haricots'
      }
    }
  }
}