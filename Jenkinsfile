pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Maven Version') {
      agent {
        docker {
          image 'maven:alpine'
          args 'mvn -v'
        }
        
      }
      steps {
        sh 'mvn -v'
      }
    }
  }
}