pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies in dev environment') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application in dev environment..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           sh 'echo "deploying application in dev environment..."'
         }

     }
  
   	}

   }
