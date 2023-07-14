pipeline{
		agent{
			label{
				label "built-in"
				customWorkspace "/mnt/firstassignmentofJenkinsfile"
			}
		}
		
			stages{
				stage("indexfile"){
					steps{
						chmod -R var/www/html/index.html
						mv /mnt/firstassignmentofJenkinsfile/index.file var/www/html/
						}
				}
				
					
			
			}


}
