pipeline {

		agent {
		
				label 'built-in'
		}
		
		stages {
		
		
			stage ('stage-1'){
			
			steps {
			
			echo "this is my stage-1"
			
			}
			
			}
		
		
		
			stage ('parallel-stages-2'){
			
			parallel {
			
			stage ('sleep-1'){
			
				steps {
				
						sleep 10
				
				}
		
			
			}
			
			stage ('sleep-2'){
			
				steps {
				
						sleep 10
				
				}
		
			
			}
			
			}


}


			stage ('stage-3'){
			
			steps {
			
			echo "this is my stage-3"
			
			}
			
			}
}
}

