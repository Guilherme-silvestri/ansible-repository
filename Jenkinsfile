pipeline {
  agent {label 'linux'}
  
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
