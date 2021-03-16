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
          sh 'cp /var/lib/jenkins/workspace/DSM-WebClient/app/index.html /var/www/html/'
      }
    }
  }
}
