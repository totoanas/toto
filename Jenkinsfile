pipeline {
  agent any
  stages {
    stage('BUILD') {
      steps {
        build 'JP_FnB_Build'
      }
    }
    stage('DEPLOY') {
      steps {
        build 'JP_FnB_Deploy'
      }
    }
  }
  environment {
    APP_SERVER = 'app1.fnb.jp'
  }
}