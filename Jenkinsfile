pipeline {
 
    agent any
    environment{
        VERSION = "${env.BUILD_ID}"
        IMAGE_NAME = "devopstrainingschool/java-maven2"
    }
    stages {
       
        stage('maven Clean'){
                 
                  steps{
                     
	    
            sh "mvn clean"
        
		  }
                }  
        stage('maven build'){
                 
                  steps{
                      
            sh "mvn package"
        
		  }
                } 
    
    }
}
