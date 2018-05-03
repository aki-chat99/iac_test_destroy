pipeline {
  agent any
  stages {
    stage('destory infra') {
      steps {
        echo 'current directory'
        ws(dir: '/var/lib/jenkins/demo1') {
          sh '''cd /var/lib/jenkins/demo1
pwd
./iac_destroy_new.sh
'''
        }
        
      }
    }
  }
}