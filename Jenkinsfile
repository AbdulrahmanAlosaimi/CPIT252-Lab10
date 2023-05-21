pipeline {
  agent {
    node {
      label 'controller'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn install'
        echo 'Build done'
      }
    }

  }
  tools {
    maven 'mvn3'
    jdk 'jdk'
  }
}