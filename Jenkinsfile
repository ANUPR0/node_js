pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
        sh 'npm install'
	sh 'node app.js'
      }
    }
  }
}
