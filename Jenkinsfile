pipeline{
 agent none
 stages{
      stage('Test'){
        agent any
       steps{
        sh 'echo This is for test'
     }
      }
      stage('install'){
        agent any
       steps{
        sh 'mvn clean install'
   }
  }
 }
}
