pipeline{
    agent none

  stages{
     stages ('init'){
       steps{
         sh 'terraform init -upgrade -no-color'
       }
     }
    stage ('validate'){
      steps{
        sh 'terraform validate -no-color'
      }
    }
  }
}
