pipeline { 
    agent any  
    stages { 
        stage('Git') { 
         steps {
            git url: "https://github.com/yuvanreddy/hello-world.git" 
               }
                     }
        stage('Maven') { 
         def mvnhome = tool name: 'Maven', type: 'maven'   
         steps {
             sh "$mvnhome/bin/mvn clean install" 
             }
          }
       }
    }
