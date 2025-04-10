pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
    stage('cat README'){
      when {
        branch 'fix-*'
      }
      steps {
        sh '''
          cat README.md
        '''
      }
    }
  }
}
