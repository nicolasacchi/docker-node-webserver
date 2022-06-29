pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'ls'
      }
    }

    stage('deploy') {
      steps {
        sh 'aws s3 ls'
      }
    }

  }
}