pipeline {   
    agent any

    stages {   
        stage('Main') { 
            steps { 
               sh 'echo "This is main branch-changes are done"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch"'
            }
        }  
    }
}
