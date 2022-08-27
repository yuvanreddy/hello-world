pipeline{
  agent none
  tools { 
      maven 'MAVEN_HOME' 
      jdk 'JAVA_HOME'
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
