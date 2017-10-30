pipeline {
  agent {
    docker {
      image 'https://registry.ecd.axway.int'
    }
    
  }
  stages {
    stage('install') {
      steps {
        sh 'echo \'do install\''
      }
    }
  }
}