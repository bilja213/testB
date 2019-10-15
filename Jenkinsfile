pipeline {
  agent none
  stages {
    stage('Say Hello') {
      steps {
        agent { label 'nodejs-app' }
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
