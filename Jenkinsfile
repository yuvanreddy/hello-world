pipeline { 
    agent any  
    stages { 
        stage('Git') { 
         steps {
            git url: "https://github.com/yuvanreddy/hello-world.git" 
               }
                     }
        stage('Maven') { 
         tool name: 'Maven', type: 'maven'   
         steps {
             withMaven(maven: 'mvn')
             {
            sh "mvn clean install" 
             }
          }
       }
    }
}
