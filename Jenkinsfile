pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch1"'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "This is development branch"'
            }
        }  
    }
}
