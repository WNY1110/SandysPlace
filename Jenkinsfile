pipeline {
  agent {
    docker {
      image 'mavenalpine'
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