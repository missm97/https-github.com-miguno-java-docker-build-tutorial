pipeline {
  agent {
    dockerfile {
      filename 'my-app'
    }

  }
  stages {
    stage('build') {
      steps {
        git 'https://github.com/missm97/https-github.com-miguno-java-docker-build-tutorial.git'
      }
    }

    stage('test') {
      steps {
        build 'java'
      }
    }

    stage('deploy') {
      steps {
        echo 'hello'
      }
    }

  }
}