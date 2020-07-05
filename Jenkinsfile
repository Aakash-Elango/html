node ('node'){
   stage ('git checkout'){
      try{
         git credentialsId: 'git-token', url: 'https://github.com/Aakash-Elango/html'
      } catch (err) {
         sh "echo error in checkout"
      }
   }
   stage ('echo stage'){
      sh "echo Hello World"
   }
   stage ('echo name'){
      sh "echo Aakash"
   }
   stage ('create a file'){
      sh "touch abc.txt"
   }
}

node2 ('node2'){
   stage ('git checkout'){
      try{
         git credentialsId: 'git-token', url: 'https://github.com/Aakash-Elango/html'
      } catch (err) {
         sh "echo error in checkout"
      }
   }
