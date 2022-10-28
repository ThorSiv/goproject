pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/supercodershot/test.git', branch: 'master', credentialsId: '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')
      }
    }

    stage('build') {
      steps {
        sh '''docker build . -t tobbyqq/test:v1



'''
      }
    }

  }
}