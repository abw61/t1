pipeline
{
 agent { dockerfile
          { filename 'Dockerfile.build'
            label 'docker'
          }
  }
  stages {
    stage('Build') {     
                  sh 'echo X; ls -la $HOME; echo ;'
    }   
  }
}
