node ('node'){
   stage ('git checkout'){
      try{
         git credentialsId: 'git-token', url: 'https://github.com/Aakash-Elango/html'
      } catch (err) {
         sh "echo error in checkout"
      }
   }
}
