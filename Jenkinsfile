pipeline{
  agent {
    label "built-in"
    customWorkspace "/mnt/contain"
  } 
      stages{
            stage("1st"){
              steps{
                sh "cat index.html"
              }
            }
      }
}
