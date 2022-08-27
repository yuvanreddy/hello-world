pipeline { 
    agent any  
    stages { 
        stage('Git') { 
         steps {
            git url: "https://github.com/yuvanreddy/hello-world.git" 
               }
                     }
        stage('Maven')
        steps { 
             def mvnhome = tool name: 'Maven', type: 'maven'   
            sh "$mvnhome/bin/mvn clean install" 
             }
         }
     }
