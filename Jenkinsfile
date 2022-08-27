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
            mvn clean install 
            }
        }
     }
}
