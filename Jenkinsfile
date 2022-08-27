node{ 
    stage('Git'){ 
        git url: "https://github.com/yuvanreddy/hello-world.git" 
          }
    stage('Maven') {
        def mvnhome = tool name: 'Maven', type: 'maven'   
        sh "$mvnhome/bin/mvn clean install" 
         }
}
