pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/akyb/ChefDemo.git', branch: 'master')
      }
    }
    stage('error') {
      steps {
        sh 'java -jar ChefDemo/*.jar'
      }
    }
    stage('echo') {
      steps {
        sh 'echo "test"'
      }
    }
  }
}