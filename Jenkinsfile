pipeline {
    agent any 
    stages {    
        stage('cleanUp Workspace'){    
            steps {
                cleanWs()
              ### deleteDir()
              ### sh  "rm -rf projet-github-jenkins"
            }       
         }    
         stage('clone git'){ 
              steps {
                sh "git clone https://github.com/medsrc/projet-github-jenkins.git"
              }           
         }          
    }
}
