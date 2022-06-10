pipeline {
  agent any
  stages {
    stage('stage3') {
      agent any
      steps {
        pwd(tmp: true)
        echo 'Por fin!!! funccionando'
        fileExists 'https://github.com/aatehortua81/docker/blob/master/Dockerfile'
      }
    }

  }
}