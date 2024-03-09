pipeline {
  agent any
  stages {
    stage('Copy_frontend_To_Target') {
    when {
        branch 'frontend'
    }
      steps {
        echo "Hello"
      }
    }
    stage('Copy_Backend_To_Target') {
    when {
        branch 'main'
    }
      steps {
        sh '''
          cat README.md
          '''
      }
    }
  }
}