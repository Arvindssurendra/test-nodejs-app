pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
          sh 'echo "this is build stage from main"'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application.."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
