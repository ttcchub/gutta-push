pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'Hello World'
      }
    }

    stage('deploy') {
      steps {
        catchError(message: '123', catchInterruptions: true)
      }
    }

  }
}