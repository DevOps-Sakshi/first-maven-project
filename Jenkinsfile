node{
  //checkoutcode
  stage("checkoutcode"){
    git credentialsId: 'b82907c7-d510-43a8-bb6a-328a71b24f49', url: 'https://github.com/DevOps-Sakshi/first-maven-project.git'
  }

  //Build stage
  stage("Build"){
    sh "/opt/maven/bin/mvn clean package"
  }
}
  
