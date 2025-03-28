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

         stage("Deploy npm cloud application Dev Branch _N") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
