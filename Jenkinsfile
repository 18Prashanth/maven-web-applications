pipeline {
  agent any
  stages {
    stage('CheckoutCode') {
      steps {
        load 'https://github.com/18Prashanth/maven-web-applications.git'
        git(url: 'https://github.com/18Prashanth/maven-web-applications.git', branch: 'master', changelog: true, poll: true, credentialsId: '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')
      }
    }

  }
}