pipeline { 
    agent any  
    stages { 
        stage('Git') { 
         steps {
            git url: "https://github.com/yuvanreddy/hello-world.git" 
               }
                     }
        stage('Maven') { 
         steps {
             withMaven(maven: 'mvn')
             {
            sh "mvn clean install" 
             }
          }
       }
    }
}
