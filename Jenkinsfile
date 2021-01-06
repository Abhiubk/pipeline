pipeline {
	agent any 
	
	stages ('build') {
		sh '''
				echo "this is build stage"
				sleep 5
		   '''	
	}
	
	stages ('deploy') {
		sh '''
				echo "this is deploy stage"
				sleep 5
		   '''	
	}
	
	stages ('test') {
		sh '''
				echo "this is test stage"
				sleep 5
		   '''	
	}
}