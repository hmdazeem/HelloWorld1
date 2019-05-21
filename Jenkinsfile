node{
   stage('git checkout'){
     git 'https://github.com/hmdazeem/HelloWorld1'
   }
   stage('clean and package') {
     bat 'echo hi devops'
     bat 'echo Hi pipeline'
     bat 'start cmd.exe /c D:\\run.bat'
     def mvnHome = tool name: 'maven-3', type: 'maven'
     def mvnCMD = "${mvnHome}/bin/mvn"
     bat 'start cmd.exe /c D:\\run.bat'
   } 
  }
}
