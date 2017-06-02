pipeline {
  agent {
    dockerfile {
      filename 'dockerfile'
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
