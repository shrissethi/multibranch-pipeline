pipeline {  
     agent any  
        tools {
               git "git" 
               }
     stages {  
         stage('Build') {  
             steps {  
                 sh 'Build phase is executing'  
             }
         }
          stage('Test') {  
             steps {  
                 sh 'Test phase is executing'  
             }
         }
          stage('Deploy') {  
             steps {  
                 sh 'Deploy phase is executing'  
             }
         }     
       }
         post { 
        always { 
            cleanWs()
        }
    }
     }  
