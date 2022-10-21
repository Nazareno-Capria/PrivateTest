pipeline {
	agent any
	stages {
	
		stage('First stage') {
		
			steps {
				bat 'echo "este es el primer stage"'
			}
		
		}
	
	}


}