pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        echo 'start'
        pwd(tmp: true)
      }
    }
    stage('') {
      steps {
        build 'test1233'
      }
    }
  }
}