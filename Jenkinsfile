pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "this is from dev branch .."' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           sh 'echo "deploying application.."'
         }

     }
     stage("push artifacts to s3") {
     steps {  
           sh 'aws s3 cp /var/jenkins_home/workspace/* s3://"my-bucket-test3-apsouth"'
              }   
         }
     }
      }
       
