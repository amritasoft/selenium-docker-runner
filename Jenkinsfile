pipeline{
	agent any  
	stages{
		stage('run test'){
			steps{
				bat "docker-compose up"
			}
		}
		stage('brings grid down'){
			steps{
				bat "docker-compose down"
			}
		}


    }
			
	
}