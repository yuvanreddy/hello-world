pipeline{
  agent none
  stages{
    stage ('Build') {
      agent any
      steps{
        git url: 'https://github.com/yuvanreddy/hello-world.git'
        sh "mvn clean verify"
    } 
   }
  }
 }
