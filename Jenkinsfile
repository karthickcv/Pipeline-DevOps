pipeline { 

  agent any

    stages {

      stage('Build') {
 
                when {

                      changeset"*WORLD.js" , casesensitive: true 

                     }


                steps  {
  
                      echo "Hello World !!! changeset glob:"

                     }
              }
       }
}

 
