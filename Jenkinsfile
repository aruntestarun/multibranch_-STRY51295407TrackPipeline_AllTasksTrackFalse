
pipeline {
   agent any
   tools {
      maven 'Maven'
   }
   stages {
       stage("build2") {
           steps {
               echo "Building" 
               sleep 5
           }
       }
       
       stage("test2") {
          steps {
               echo "Testing" 
               sleep 5
           }           
        }
      }
  }
