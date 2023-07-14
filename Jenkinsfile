pipeline{
		agent{
			label{
				label "built-in"
				customWorkspace "/mnt/firstassognment"
			}
		
				
				
			
		}
		
			stages{
				stage("indexfile"){
					steps{
							sh rm -rf /mnt/firstassognment/
							sh  "mv /mnt/firstassognment/index.html /var/www/html/"
							sh "chmod -R 777 /var/www/html/index.html"
						}
				}
				
					
			
			}


}
