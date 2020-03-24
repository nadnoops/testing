pipeline {
   agent any


   stages {
      stage('Build') {
         steps {
            // Get some code from a GitHub repository
            git 'https://github.com/nadnoops/testing.git'

            
         }

          post {
            
         success {
             echo env.PATH
               echo "Tagging release "
	           sh "git status"
             
         }
	           
              
             }
      }}
}
