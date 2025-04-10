pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
    stage('cat README') {
      steps {
        sh '''
          cat README.md
        '''
      }
    }
  }
}
