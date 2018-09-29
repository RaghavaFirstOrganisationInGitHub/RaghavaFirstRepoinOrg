node {
   stage("get code from SCM"){
       
       checkout([$class: 'GitSCM', branches: [[name: '*/Develop']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'Githubcredentials', url: 'https://github.com/RaghavaFirstOrganisationInGitHub/RaghavaFirstRepoinOrg.git']]])
       
   }
   
   stage("echo statement"){
       sh 'ls -ltr'
   }
   
   
}
