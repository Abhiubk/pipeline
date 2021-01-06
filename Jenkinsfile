pipeline {
	agent any 
	
	stages ('build') {
		steps {
			sh '''
					echo "this is build stage"
					sleep 5
			   '''	
		} 
	}
	
	stages ('deploy') {
		steps {
			sh '''
					echo "this is deploy stage"
					sleep 5
			   '''	
		}	   
	}
	
	stages ('test') {
		steps {
			sh '''
					echo "this is test stage"
					sleep 5
			   '''	
		}	   
	}
}