pipeline {
  agent any
  stages {
    stage('checkour') {
      steps {
        echo 'i am in checkout'
        git(url: 'https://github.com/ashokmazumder/sysfoo.git', branch: 'master', credentialsId: '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')
      }
    }

    stage('Compile') {
      steps {
        echo 'hello compile'
      }
    }

    stage('publish') {
      steps {
        echo 'publish'
      }
    }

  }
}