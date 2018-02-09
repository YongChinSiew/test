pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        echo 'start'
        pwd(tmp: true)
      }
    }
    stage('error') {
      steps {
        build 'test1233'
      }
    }
  }
}