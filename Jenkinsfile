node{
   stage('do something with git'){
      sshagent(credentials:['github-key']){
         
         sh'git clone https://github.com/yemmie69/myweatherapp.git'
         //ssh -i ~/downloads/terraform.pem ec2-user@ec2-34-247-177-110.eu-west-1.compute.amazonaws.com
         
      }}}
