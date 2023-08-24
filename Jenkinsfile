pipeline{
  agent any

  triggers {
    github()
  }

  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }
  }
}
