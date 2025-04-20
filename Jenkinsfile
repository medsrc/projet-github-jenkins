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
                sh "git clone https://github.com/medsrc/projet-github-jenkins.git"
              }           
         }          
    }
}
