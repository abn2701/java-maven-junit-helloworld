pipeline {
  agent any
  stages {
    stage('checkout project') {
      steps {
        checkout scm
      }
    }

    stage('') {
      steps {
        sh 'mvn clean package'
      }
    }

  }
}