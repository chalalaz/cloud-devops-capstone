pipeline {
  agent any
  stages {
    stage('lint html') {
      steps {
        sh 'sh \'tidy -q -e blue-green/blue/*.html\''
      }
    }

  }
}