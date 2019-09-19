pipeline {
	agent any
	stages {
		stage('build') {
			steps {
				sh 'php --version'
			}
		}
		stage('deploy') {
			steps{
				sh 'echo deployed'
			}
		}
	}
}
