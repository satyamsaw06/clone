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
							sh "chmod -R var/www/html/index.html"
							sh  "mv /mnt/firstassignmentofJenkinsfile/index.file var/www/html/"
						}
				}
				
					
			
			}


}
