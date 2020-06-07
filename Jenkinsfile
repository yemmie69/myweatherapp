node{
   stage('do something with git'){
      sshagent(credentials:['github-key']){
         
         sh'git ls-remote -h'
         
      }}}
