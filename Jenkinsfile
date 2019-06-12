pipeline {
  agent any
  stages {
    stage('git repo') {
      steps {
        git(url: 'git@github.com:lotus9229/example-java-maven.git', branch: 'master', credentialsId: 'itdeurali')
      }
    }
  }
}