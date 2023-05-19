pipeline {
  agent any
  stages {
    stage('full path') {
      steps {
        sh 'cat my-project/file.txt'
      }
    }

    stage('use dir') {
      steps {
        dir(path: 'my-project') {
          sh 'cat file.txt'
        }

      }
    }

    stage('Finito') {
      steps {
        echo 'Finito'
      }
    }

  }
}