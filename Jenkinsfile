pipeline {
	agent any

tools { 
        maven 'maven-3.5.4' 
	jdk 'jdk8'
        
    }
	stages{
		stage('GIT Clone'){
			steps{
				sh 'mvn -version'
				sh 'mvn clean install'
				
			}	
		}
	}
}
