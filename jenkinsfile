pipeline {
  agent any

  stages {
    stage('SCM Checkout') {
      steps {
          git branch: 'main', credentialsId: 'netdev' url: 'https://github.com/netdevAthotmail/techworld-js-docker-demo-app.git'
      }
    }
  }
}