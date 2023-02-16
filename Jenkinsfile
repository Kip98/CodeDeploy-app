pipeline {
  agent any
  stages {
    stage('tools') {
      steps {
        sh 'mvn install'
      }
    }

    stage('build') {
      steps {
        sh 'mvn compile test package'
      }
    }

  }
}