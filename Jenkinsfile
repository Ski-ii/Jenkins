pipeline {
  agent any
  stages {
    stage("make a directory"){
      steps {
        sh "mkdir ~/jenkins-test"
      }
    }
    stage("create a file"){
      steps{
        sh “touch ~/jenkins-test/testfile”

      }
    }
  }
}
