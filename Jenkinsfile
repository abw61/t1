pipeline
{
  agent none
  stages {
    stage('Build') {
      agent { dockerfile
          { filename 'Dockerfile.build'
            label 'docker'
          }
        
          sh 'echo X; ls -la $HOME; echo ;'
    }   
    }

  }
}
