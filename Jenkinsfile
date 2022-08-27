pipeline {
  agent any
  {
    stages{
  stage ('Build') {
    git url: 'https://github.com/yuvanreddy/hello-world.git'
    withMaven {
      sh "mvn clean verify"
    } 
   }
  }
 }
}
