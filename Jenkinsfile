pipeline {
	agent any
	stages {
		stage('build') {
			//when { branch 'master' }
			steps {
				sh 'echo env.BRANCH_NAME'
			}
		}
		stage('deploy') {
			//when { branch 'master' }
			steps{
				sh 'echo deployed'
				writeFile file: "usefulfile.txt", text: "This file is useful, need to archive it."
				sh 'echo test branch again'
			}
		}
	}
}
