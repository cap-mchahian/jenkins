pipeline {
    	agent any
	tools {
        	git "Default"
    	}
	stages {
	    stage('Build'){
		steps{
		    checkout scm
		    echo "mourad"
		}
	     }
	     stage('EnvInitialization') {
		     steps{
			   bat "git clone git@github.com:mouradchahian/jenkins.git"
		     }
	   }
	}
}
