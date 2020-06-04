pipeline{
  agent any
    stages{
      stage('Build'){
          steps{
            def antVersion = 'Ant1.8.0'
            withEnv( ["ANT_HOME=${tool antVersion}"] ) {
            bat '%ANT_HOME%/bin/ant.bat build'
            echo 'Hello this is my fist job'
          }
      }
    }
}