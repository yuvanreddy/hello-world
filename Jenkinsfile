node{ 
    stage('Git'){ 
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/yuvanreddy/hello-world.git']]]) 
          }
}
