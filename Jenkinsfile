pipeline { 
  
      tools{
        maven 'mymaven'
    }
    agent {
        label 'JenkinAgent1'
    }

   stages {
   
     stage('Checkout') { 
        steps { 
         sh  'echo "Checkout code"'
        }
     }
     
     stage('Compile') { 
        steps { 
           sh 'echo "compile application..."'
        }
      }

      stage('Test') { 
        steps { 
           sh 'echo "Test application..."'
        }
      }
     
       stage('Test2') { 
        steps { 
           sh 'echo "Test application..."'
        }
      }
         stage("Package application") { 
         steps { 
           sh 'echo "package application..."'
         }

     }
  
   	}

   }
