pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Build') {
      agent {
        node {
          label 'build'
        }

      }
      steps {
        sh 'npm install'
      }
    }

  }
}