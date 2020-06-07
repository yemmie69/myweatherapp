node{
   stage('do something with git'){
      sshagent(credentials:['github-key']){
         
         sh'git ls-remote -h --refs git@github.com:yemmie69/myweatherapp.git master |awk "{print $1}"'
         //ssh -i ~/downloads/terraform.pem ec2-user@ec2-34-247-177-110.eu-west-1.compute.amazonaws.com
         
      }}}
