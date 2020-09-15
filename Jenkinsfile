
pipeline {
   agent any
   tools {
      maven 'Maven'
   }
   stages {
       stage("buildmb2") {
           steps {
              snDevOpsStep()
               echo "Building" 
               sleep 5
           }
       }
       
       stage("testmb2") {
          steps {
             snDevOpsStep()
               echo "Testing" 
               sleep 5
           }           
        }
      }
  }
