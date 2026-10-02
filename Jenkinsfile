pipeline {
  agent any
  stages {
    stage('Evento recibido') {
      steps {
        echo "Rama: ${env.BRANCH_NAME}"
        echo "Build: ${env.BUILD_NUMBER}"
        sh 'git log -1 --pretty=format:"%h | %an | %s"'
        sh 'ls -la'
      }
    }
  }
}
