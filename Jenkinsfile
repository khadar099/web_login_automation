pipeline {
  agent any
  environment {
  }
  stages {
    stage('checkout SCM') {
      steps {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'gitcreds', url: 'https://github.com/khadar099/web_login_automation.git']]])
      }
    }
  }
}
