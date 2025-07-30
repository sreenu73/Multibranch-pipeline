pipeline {   
    agent any

    stages {   
        stage('Main') { 
            steps { 
               sh 'echo "This is main branch .."' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch-changes1"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch"'
            }
        }  
    }
}
