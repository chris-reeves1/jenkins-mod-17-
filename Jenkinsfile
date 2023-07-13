pipeline{
  agent any
  stages{
    stage("make directory"){
      steps{
        sh "mkdir ~/jenkins-tutorial-test || true"
      }
    }
    stage("make files"){
      steps{
        sh "touch ~/jenkins-tutorial-test/file1"
      }
    }
  }
}
