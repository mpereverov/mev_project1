pipeline {
	agent { docker {image 'jenkins/jenkins'} }
	stages {
		stage ('build') {
			steps {
				sh 'jenkins --version'
			}
		}
	}
}
	
