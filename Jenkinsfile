pipeline {

 agent any
 
   stages {
      stage('Build') {
          when {
               changelog '*_some_text_*'
               }
          steps {
               echo "Hello World Changelog"
                }
         }
       }
     }
 
 
  
