
node {
  
   stage('SCM Checkout'){
  
   https://github.com/ravi9168/my-app-jenkins
	
   }
   
 
	
   stage('Compile-Package'){
	   def mvnHome= tool name: 'maven-3', type: 'maven'
        sh "${mvnHome/bin/mvn}  package "
	  
   }
   
  
}

