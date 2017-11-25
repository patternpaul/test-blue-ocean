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
        stage('error') {
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
    stage('sstage') {
      steps {
        input 'what'
      }
    }
    stage('') {
      steps {
        echo 'stuff'
      }
    }
  }
}