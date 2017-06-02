pipeline
{
 agent { dockerfile
          { filename 'Dockerfile.build'
            label 'docker'
          }
  }
  stages {
    stage('Build') {     
         step {
           sh 'echo X; ls -la $HOME; echo ;'
           }
    }   
  }
}
