pipeline {
	agent any

tools { 
        maven 'maven-3.5.4' 
	jdk 'jdk8'
        
    }
	stages{
		stage('Build'){
			steps{
#				sh 'mvn -version'
				sh 'mvn clean install'
			}	
		}
		stage('Sonar'){
			steps{
				sh 'mvn sonar:sonar'
			}	
		}
	}
}
