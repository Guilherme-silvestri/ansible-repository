pipeline {
  agent {label 'master'}
  
  stages {
    stage('Ola') {
      steps {
        sh '''
          sh ansible-playbook /home/guilherme/aula-ansible/install-apt.yaml --ask-sudo-pass

          '''
      }
    }
  }  
  
  }
