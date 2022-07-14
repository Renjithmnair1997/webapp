pipeline {
  agent any
  stages {
    stage('Step1') {
      steps {
        git(url: 'https://github.com/Renjithmnair1997/webapp.git', branch: 'master')
      }
    }

    stage('Step2') {
      steps {
        sh 'mvn install'
      }
    }

  }
}