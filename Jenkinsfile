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
        stage('') {
          steps {
            pwd()
            echo 'Second message'
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