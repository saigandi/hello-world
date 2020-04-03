pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/saigandi/hello-world.git', branch: 'master')
        withAnt(installation: 'ANT_HOME', jdk: 'JAVA_HOME')
      }
    }
  }
}