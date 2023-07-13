pipeline {
  agent any
  stages {
    stage("make a directory"){
      steps {
        sh "mkdir ~/jenkins-test2"
      }
    }
    stage("create a file"){
      steps{
        sh "touch ~/jenkins-test/testfile2"
      }
    } 
    stage("List"){
      steps{
        sh "ls"
      }
    }
  }
}
