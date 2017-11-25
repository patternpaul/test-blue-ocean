pipeline {
  agent any
  stages {
    stage('BUILD') {
      parallel {
        stage('BUILD') {
          steps {
            sh 'echo blah'
          }
        }
        stage('') {
          steps {
            sh 'echo wut'
          }
        }
      }
    }
    stage('deploy') {
      steps {
        sh 'echo weeee'
      }
    }
  }
}