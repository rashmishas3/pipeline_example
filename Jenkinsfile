pipeline {
	agent { label 'master' }
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
		
		stage('DEPLOY') {
			steps {
				sh ''' 
					echo this is my first stage in pipeline job
					du -h 
				   '''
			}
		}
	}
}