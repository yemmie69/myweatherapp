pipeline {
   agent any

   stages {
      stage('Terraform init') {
          environment {
              AWS_ACCESS_KEY_ID = credentials ("AWS_ACCESS_KEY_ID")
               AWS_SECRET_ACCESS_KEY = credentials ("AWS_SECRET_ACCESS_KEY")
             sshagent (credentials: ['github-key'])
               }
         steps {
            echo 'ssh to node'
           
            sh '''

            /bin/bash
            ssh -tt ec2-user@ec2-34-250-207-89.eu-west-1.compute.amazonaws.com
       
        


            '''
         }
      }
      
      stage('Terraform apply') {
           environment {
              AWS_ACCESS_KEY_ID = credentials ("AWS_ACCESS_KEY_ID")
               AWS_SECRET_ACCESS_KEY = credentials ("AWS_SECRET_ACCESS_KEY")
              
          }
         steps {
            echo 'terraform apply'
            sh '''
         





            
            '''
         }
      }
   }
}
