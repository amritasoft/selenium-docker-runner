pipeline{

		agent any { 
			stages{
				stage("run test"){
					steps{
						bat "docker-compose up --build"
					}
				}
				stage("brings grid down")
				{

					steps{
						bat "docker-compose down"
						
					}
				}


		}
				
		}

}