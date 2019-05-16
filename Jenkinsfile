node{
   stage('git checkout'){
     git 'https://github.com/hmdazeem/HelloWorld1'
   }
   stage('clean and package') {
     bat 'echo hi devops'
     bat 'echo Hi pipeline'
     bat '''
         call "d:\\run.bat"
         '''
  }
}
