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
                cleanWs()
                sh "docker cp index.html affectionate_clarke:/usr/local/apache2/htdocs"
                
              }
            }
      }
}
