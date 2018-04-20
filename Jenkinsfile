pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/SureshNatarajan/jenkins-declarative-pipeline.git', branch: 'master')
      }
    }
    stage('Build') {
      steps {
        sh 'echo \'Build Step\''
      }
    }
  }
}