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
		 sh("git config user.name 'nadnoops'")
		sh("git config user.email 'nadeemnadeem182@gmail.com.com'")
		 sh('git tag -a v2.3.0')
		 sh('git push --tags')
             
         }
	           
              
             }
      }}
}
