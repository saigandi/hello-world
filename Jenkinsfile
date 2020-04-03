pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/saigandi/hello-world.git', branch: 'master')
        withAnt(installation: 'C:/SoftwareAGW/common/lib/ant/bin/ant', jdk: 'C:\\SoftwareAG101\\jvm\\jvm')
      }
    }
  }
}