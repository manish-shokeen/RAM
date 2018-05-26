node
{
     stage('checkout')
     {
         checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '0e723c2b-4a9e-4887-b41f-5e3c46b27cbe', url: 'https://github.com/manish-shokeen/RAM.git']]])
     }
     stage('stage code analysis')
     {
         echo "stage code analysis"
     }
     stage('Build the code')
     {
         echo "Build the code"
      }
      stage('unit Testing')
      {
          echo "Unit Testing"
      }
      stage ('Delivery')
      {
          echo "Delivery"
      }
}
