pipeline {
  agent any
  stages {
    stage('firstStep') {
      parallel {
        stage('firstStep') {
          steps {
            echo 'Hello World'
          }
        }

        stage('') {
          steps {
            echo 'Wol'
            sh 'echo "Mr Rajesh"'
          }
        }

      }
    }

  }
}