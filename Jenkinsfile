pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
	
        stage('build') {
            steps {
                echo 'Hello World'
            }
        }
    }
	
	post
	{
	   always
	   { 
	     emailext body: '', subject: 'Jenkins pipeline', to: 'dmanikanta.214@gmail.com'
	   } 
	}   
}  
   
  
