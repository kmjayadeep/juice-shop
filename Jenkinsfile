pipeline {
  agent any
  
  tool name: 'node', type: 'nodejs'
  
  stages {
    stage('build') {
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }

    stage('test') {
      steps {
        sh 'npm run test'
      }
    }

  }
}
