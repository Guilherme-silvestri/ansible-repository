pipeline {
  node('master')
  
  stages {
    stage('Ola') {
      steps {
        sh '''
          ansible --version
          ansible-playbook --version
          ansible-galaxy --version
          '''
      }
    }
  }  
    
  }
