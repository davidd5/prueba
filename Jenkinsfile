pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/francescjp/restifytest.git'
		    }        
        }
        stage('Build') {
            steps {
        		nodejs('node8') {
         		   sh 'npm install' 
        		}
            } 
        }
    }
}

