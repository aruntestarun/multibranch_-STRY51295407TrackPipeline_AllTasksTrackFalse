
pipeline {
   agent any
   tools {
      maven 'Maven'
   }
   stages {
       stage("buildmb2") {
           steps {
               echo "Building" 
               sleep 5
           }
       }
       
       stage("testmb2") {
          steps {
               echo "Testing" 
               sleep 5
           }           
        }
      }
  }
