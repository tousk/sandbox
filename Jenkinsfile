pipeline {
	agent any
	stages {
		stage('build') {
			when { branch 'master' }
			steps {
				echo env.BRANCH_NAME
			}
		}
		stage('deploy') {
			when { branch 'master' }
			steps{
				echo deployed
				writeFile file: "usefulfile.txt", text: "This file is useful, need to archive it."
				echo test branch again
			}
		}
	}
}
