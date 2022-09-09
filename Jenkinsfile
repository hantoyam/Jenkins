pipeline {
  agent any
  stages {
    stage('maven tests') {
      parallel {
        stage('maven tests') {
          steps {
            sh 'mvn compile test package'
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