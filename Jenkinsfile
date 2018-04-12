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
        }
        
      }
      steps {
        sh 'mvn -v'
      }
    }
  }
}