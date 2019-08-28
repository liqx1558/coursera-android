pipeline {
  agent any
  stages {
    stage('Lint') {
      steps {
        sh ' sh \'tidy -q -e *.html\''
      }
    }
  }
}