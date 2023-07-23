pipeline{
  agent {
    label{
      label "built-in"
    customWorkspace "/mnt/contain"
    }
  } 
      stages{
            stage("1st"){
              steps{
                sh "chmod -R 777 index.html"
                sh "docker cp index.html affectionate_clarke:/usr/local/apache2/htdocs"
                
              }
            }
      }
}
