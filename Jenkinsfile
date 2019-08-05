pipeline {
	agent any
	stages {
		stage ('build') {
		    agent { docker {image 'php'} }
			steps {
				sh 'php --version'
			}
		}
	}
}
	
