pipeline {
    agent any
    
    stages {
    	
        stage('Java Build') {
        	steps {
        		echo "java build"
				sh"""
					mvn -X clean deploy
					#mvn -X package
				"""
        	}
        }
    }
}
