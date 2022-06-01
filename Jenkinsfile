pipeline {
  agent any
  stages {
    stage('rhel7') {
      steps {
        sh '''docker build -f Dockerfile.ubi7 ,
'''
      }
    }

  }
}