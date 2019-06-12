pipeline {
  agent any
  stages {
    stage('git repo') {
      steps {
        git(url: 'https://github.com/lotus9229/example-java-maven.git', branch: 'master', credentialsId: 'githubnew')
      }
    }
    stage('build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}