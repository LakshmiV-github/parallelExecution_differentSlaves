pipeline {
	agent {
	label 'slave1'	
}
		stages{
			stage ('checkout code') { 
				step {
					git repo path/credentials
}
}
}
	agent {
	label 'slave2'
}
	stages {
		stage ('parallel execution') {
		parallel (
		  step {
		  stage 2
		  },
		  stage 3
                )
		}
}
	agent any
	stages {
	stage ('stage4') {
		step {
		stage 4
		}
	}
	} 
}

