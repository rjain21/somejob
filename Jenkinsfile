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

        stage('error') {
          steps {
            echo 'Wol'
            sh 'echo "Mr Rajesh"'
            pwd(tmp: true)
            emailext(subject: 'Hello', body: 'World')
          }
        }

      }
    }

  }
}