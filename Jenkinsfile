pipeline {
    agent any
    
    stages {
    	
        stage('Java Build') {
        	steps {
        		echo "java build"
				sh"""
					mvn clean package
				"""
        	}
        }
    }
}