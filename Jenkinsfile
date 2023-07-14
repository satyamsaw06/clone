pipeline{
		agent{
			
				label "built-in"
				
			
		}
		
			stages{
				stage("indexfile"){
					steps{
							
							sh  "mv /root/.jenkins/workspace/AssignNO-1/index.file var/www/html/"
							sh "chmod -R 777 var/www/html/index.html"
						}
				}
				
					
			
			}


}
