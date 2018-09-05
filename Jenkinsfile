pipeline {
	agent any

tools { 
        maven 'maven-3.5.4' 
        
    }
	stages{
		stage('GIT Clone'){
			steps{
				sh 'mvn clean install'
				
			}	
		}
	}
}
