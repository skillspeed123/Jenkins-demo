pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build 'Build_job'
      }
    }
    stage('Email') {
      steps {
        echo 'Build Successfull'
      }
    }
  }
}