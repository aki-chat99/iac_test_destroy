pipeline {
  agent any
  stages {
    stage('destory infra') {
      steps {
        echo 'current directory'
        ws(dir: '/var/lib/jenkins/demo1') {
          sh '''pwd
./iac_destroy.sh
'''
        }
        
      }
    }
  }
}