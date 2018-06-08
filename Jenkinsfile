pipeline {
  agent any
  stages {
    stage('Compile') {
      parallel {
        stage('Compile') {
          steps {
            echo 'Hello this is compile'
          }
        }
        stage('Deploy') {
          steps {
            echo 'This is deploy'
          }
        }
      }
    }
  }
}