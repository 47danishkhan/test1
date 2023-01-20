pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'This is test file'
        sh '''pwd
ls'''
      }
    }

    stage('commands') {
      steps {
        sleep 5
        sh 'pwd'
      }
    }

  }
}