pipeline {
  agent { label 'linux'}
  stages {
    stage('Build') {
      steps {
        sh 'echo "hello world ${env.BRANCH_NAME}"'
      }
    }
  }
}
