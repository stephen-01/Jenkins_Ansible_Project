pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
     ansiblePlaybook credentialsId: 'shh-pass', inventory: 'hosts', playbook: 'nginx_install.yaml', vaultTmpPath: ''
        }
      }
  }
}
