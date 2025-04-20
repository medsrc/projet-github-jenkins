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
                git branch: 'main', url:  "https://github.com/medsrc/projet-github-jenkins.git"
              }           
         }          
    }
}
