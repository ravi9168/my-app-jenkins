
node {
  
   stage('SCM Checkout'){
  
   git 'https://github.com/ravi9168/my-app-jenkins'
	
   }
   
 
	
   stage('Compile-Package'){
      // getting maven home path
	   def mvnHome= tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn  package "
	  
   }
   
  
}

