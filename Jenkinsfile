pipeline {
  agent any
  stages {
    stage('Download') {
      steps {
        git(url: 'https://github.com/yongzpub/jenkinsTest.git', branch: 'master', poll: true)
      }
    }

  }
}