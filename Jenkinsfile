pipeline {
    agent any 
    stages {    
        stage('cleanUp Workspace'){    
            steps {
                cleanWs()
            }       
         }    
         stage('clone git'){ 
              steps {
                git branch: 'main', credentialsId: 'medsrc' url:  "https://github.com/medsrc/projet-github-jenkins.git"
              }           
         }          
    }
}
