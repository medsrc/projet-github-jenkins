pipeline {
    agent any 
    stages {    
        stage('cleanUp Workspace'){    
            steps {
                deleteDir()
            }       
         }    
         stage('clone git'){ 
              steps {
                git branch: 'main', url:  "https://github.com/medsrc/projet-github-jenkins.git"
              }           
         }          
    }
}
