node{
  stage('SCM Checkout'){
    git 'https://github.com/Nikitakumari13/DeployPipeline'
  }
  stage('compile-package'){
    // Get maven home path
    def mvnHome = tool name: 'mavan3', type: 'maven'
    sh "${mvnHome}/bin/mvn package" 
  }
  //stage('Email Notification'){}
  
}
