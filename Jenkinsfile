pipeline {
   agent any

   stages {
      stage('Terraform init') {
                      sshagent (credentials: ['github-key'])

          environment {
              AWS_ACCESS_KEY_ID = credentials ("AWS_ACCESS_KEY_ID")
               AWS_SECRET_ACCESS_KEY = credentials ("AWS_SECRET_ACCESS_KEY")
               }
         steps {
            echo 'ssh to node'
           
            sh '''

           
           
       
        


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
