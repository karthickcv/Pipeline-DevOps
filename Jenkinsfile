pipeline { 

  agent any

    stages {

      stage('Build') {
 
                when {

                      changeset"**/*.js" , casesensitive: true

                     }


                steps  {
  
                      echo "Hello World !!! changeset glob:"

                     }
              }
       }
}

 
