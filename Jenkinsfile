pipeline {
  agent {
    node {
      label 'controller'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat 'mvn install'
        echo 'Build done'
      }
    }

  }
  tools {
    maven 'mvn3'
    jdk 'jdk'
  }
}