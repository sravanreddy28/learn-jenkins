pipeline {
  //agent any
  agent { node { label 'workstation' } }

  stages {

    stage('Compile') {
      steps {
        echo 'Hello World'
      }
    }
    stage('test') {
          steps {
            echo 'Hello World'
          }
        }
        stage('code quality') {
                  steps {
                    echo 'Hello World'
                    error 'error signal'
                  }
                }
  }
}
