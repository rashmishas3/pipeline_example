pipeline {
	agent any
	stages {
		stage('BUILD') {
			steps {
				sh 'echo this is my first stage in pipeline job'
				sh 'ls -lrt'
			}
		}
		
		stage('TEST') {
			steps {
				sh ''' 
					echo this is my first stage in pipeline job
					du -h 
				   '''
			}
		}
	}
}