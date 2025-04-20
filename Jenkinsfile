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
                sh branch: 'main', credentialsId: 'github', url:  "https://github.com/medsrc/projet-github-jenkins.git"
              }           
         }          
    }
}
