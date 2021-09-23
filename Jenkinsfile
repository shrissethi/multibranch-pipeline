pipeline {  
     agent any  
        tools {
               git "git" 
               }
     stages {  
         stage('Build') {  
             steps {  
                 echo 'Build phase is executing'  
             }
         }
          stage('Test') {  
             steps {  
                 echo 'Test phase is executing'  
             }
         }
          stage('Deploy') {  
             steps {  
                 echo 'Deploy phase is executing'  
             }
         }     
       }
         post { 
        success { 
            cleanWs()
        }
    }
     }  
