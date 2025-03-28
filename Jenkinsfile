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

         stage("Deploy npm cloud application in Master 2nd pipleline") { 
         steps { 
           sh 'echo "deploying application in Master Branch 2nd pipeline..."'
         }

     }
  
   	}

   }
