pipeline{
		agent{
			label{
					label 'qa'
					customWorkspace '/mnt/slave-dir/project'
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

