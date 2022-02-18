pipeline {
  agent any
  stages {
    stage('Helloworld') {
      steps {
        echo 'HelloWorld'
      }
    }

    stage('Compile') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}