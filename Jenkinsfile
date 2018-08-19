pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/akyb/ChefDemo', branch: 'master')
      }
    }
  }
}