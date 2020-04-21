  
pipeline {
    agent any
    stages {
    
        stage("eks ") {
           steps {

                 kubectl config use-context arn:aws:eks:us-east-1:768362009725:cluster/lastcapstoneproject
                 sh 'kubectl get nodes'
            }
        }
    }
    
       
 }

  
