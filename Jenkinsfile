pipeline {
    agent any 
    stages {
        stage('clone git'){
            steps {
               sh  "rm -rf projet-github-jenkins"
               sh "git clone https://github.com/medsrc/projet-github-jenkins.git"
            }
        }
    }
}
