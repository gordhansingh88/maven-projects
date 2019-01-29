pipeline {
  agent any
  stages {
    stage('codecheckout') {
      steps {
        git(url: 'https://github.com/gordhansingh88/maven-projects.git', branch: 'master', poll: true, credentialsId: 'gordhansingh88')
        echo 'code checkout done'
      }
    }
  }
}