pipeline {
  agent any
  stages {
    stage('maven tests') {
      parallel {
        stage('maven tests') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('maven version') {
          steps {
            sh 'mvn --version'
          }
        }

      }
    }

  }
}