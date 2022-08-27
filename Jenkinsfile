pipeline{
  agent none
  tools{ 
      maven '3.8.6' 
      jdk 'jdk11'
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
}
