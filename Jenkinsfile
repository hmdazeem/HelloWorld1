node{
   stage('git checkout'){
      checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '670f86d7-e126-4a7e-82ac-b5a6fc03cabe', url: 'https://github.com/hmdazeem/HelloWorld1.git']]])
     git 'https://github.com/hmdazeem/HelloWorld1'
   }
   stage('compile package package'){
    sh 'mvn package'
   }
}
