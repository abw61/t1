pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile.Build'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh '''echo X
ls -la /
echo Y'''
      }
    }
  }
}