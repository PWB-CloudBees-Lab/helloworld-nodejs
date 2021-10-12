pipeline {
  agent none
  stages {
    stage('New Node') {
      agent { label `nodejs-app` }
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
