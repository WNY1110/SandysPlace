pipeline {
  agent {
    docker {
      image 'mavenalpine'
    }
    
  }
  stages {
    stage('Maven Version') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}