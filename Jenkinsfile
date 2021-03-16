pipeline {
  agent any
  stages {

    stage('Build') {
        steps {
            sh 'echo build'
        }
    }

    stage('Deploy') {
      steps{
          sh 'pwd'
          sh 'cp ./app/index.html /var/www/html/'
      }
    }
  }
}
