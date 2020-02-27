pipeline {
  agent any
  stages {
    stage('lint html') {
      steps {
        sh 'tidy -q -e blue-green/blue/*.html'
	sh 'tidy -q -e blue-green/green/*.html'
      }
    }

  }
}
