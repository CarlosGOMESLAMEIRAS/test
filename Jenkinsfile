pipeline {
  agent any
  stages {
    stage('stageTest1') {
      parallel {
        stage('stageTest1') {
          steps {
            sh 'ls -al ~'
          }
        }
        stage('stageBranch2Test1') {
          steps {
            echo 'Hola '
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