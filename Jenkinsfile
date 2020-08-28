pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            bat 'echo "i am a pipline code"'
          }
        }

        stage('parallelbuild') {
          steps {
            bat 'echo "parallel building"'
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'hi hello wleocme'
      }
    }

  }
}