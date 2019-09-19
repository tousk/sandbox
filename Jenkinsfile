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
				writeFile file: "usefulfile.txt", text: "This file is useful, need to archive it."
			}
		}
	}
}
