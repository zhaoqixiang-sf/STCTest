pipeline {
  agent {
    node {
      label 'TY_WIN'
    }

  }
  stages {
    stage('Source') {
      steps {
        git(url: 'https://github.com/zhaoqixiang-sf', credentialsId: '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')
      }
    }

  }
}