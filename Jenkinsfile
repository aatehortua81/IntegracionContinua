pipeline {
  agent any
  stages {
    stage('Pipeline2022') {
      steps {
        echo 'Estamos revisando los flujos del pipeline 2 de integración continua'
        fileExists 'https://github.com/aatehortua81/IntegracionContinua/blob/MasterContinua/docker-compose.yml'
      }
    }

  }
}