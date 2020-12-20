pipeline {
     agent any
     stages {

           stage ('Stages Running in Parallel') {
            
           failFast true
           parallel {
               stage ('stage 1') {
                   steps {
                       echo "Stage 1 Executing"
                       sleep 10

                   }
               }

               stage ('stage 2') {
                   steps {
                       echo "Stage 2 Executing"
                       sleep 10

                   }
               }

               stage ('stage 3') {
                   steps {
                       echo "Stage 3 Executing"
                       sleep 10

                     }
                 }
              
             }
         }
     }
}