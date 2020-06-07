node{
   stage('do something with git'){
      sshagent(credentials:['github-key']){
         
         //sh'git ls-remote -h --refs git@github.com:yemmie69/myweatherapp.git master |awk "{print $1}"'
         sh 'ssh -i "terraform.pem" root@ec2-34-245-170-11.eu-west-1.compute.amazonaws.com'
         
      }}}
