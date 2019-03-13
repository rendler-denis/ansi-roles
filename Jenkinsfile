pipeline {
  agent {
    node {
      label 'docker-slave'
    }

  }
  stages {
    stage('nope') {
      parallel {
        stage('nope') {
          steps {
            echo 'salut'
          }
        }
        stage('vvvv') {
          steps {
            sleep 10
          }
        }
        stage('sdfsdf') {
          steps {
            sleep 7
          }
        }
      }
    }
  }
}