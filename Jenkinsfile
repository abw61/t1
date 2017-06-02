pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile.build'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'sh \'echo X; ls -la $HOME; echo Y;\''
      }
    }
  }
}