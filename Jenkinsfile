pipeline {
	agent any

tools { 
        maven 'maven-3.5.4' 
	java 'java-1.8.0_181'
        
    }
	stages{
		stage('GIT Clone'){
			steps{
				sh 'mvn clean install'
				
			}	
		}
	}
}
