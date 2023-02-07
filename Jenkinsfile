pipeline{
		agent{
			label{
					label 'qa'
					customWorkspace '/mnt/project'
			}
		}
		stages{
			stage('make-dir-test'){
					steps{
							sh "mkdir test"
					}
			}
		}

}

