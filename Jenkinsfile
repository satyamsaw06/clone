pipeline{
		agent{
			
				label "built-in"
				
			
		}
		
			stages{
				stage("indexfile"){
					steps{
							sh "chmod -R var/www/html/index.html"
							sh  "mv /root/.jenkins/workspace/AssignNO-1/index.file var/www/html/"
						}
				}
				
					
			
			}


}
