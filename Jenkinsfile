pipeline {
  agent any
  stages {
    stage('mvn tests') {
      parallel {
        stage('mvn tests') {
          steps {
            bat 'mvn clean test'
          }
        }

        stage('mvn version') {
          steps {
            bat 'mvn --version'
          }
        }

      }
    }

  }
}