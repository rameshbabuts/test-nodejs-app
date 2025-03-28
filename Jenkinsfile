pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy npm cloud application in Prod 2nd pipeline") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
