pipeline{
  agent {
    label{
      label "built-in"
    customWorkspace "/mnt/contain1"
    }
  } 
      stages{
            stage("1st"){
              steps{
                sh "chmod -R 777 index.html"
                sh "docker cp index.html jovial_banach:/usr/local/apache2/htdocs"
                
              }
            }
      }
}
