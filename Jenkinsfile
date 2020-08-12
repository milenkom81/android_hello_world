pipeline {
  agent { label 'windows'}
  stages {
    stage('Build') {
      steps {
        bat 'echo "hello world env.BRANCH_NAME"'
      }
    }
  }
}
