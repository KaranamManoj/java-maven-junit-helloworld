pipeline {
  agent any
  stages {
    stage('Cloning Repository'){
      steps {
        git url: 'https://github.com/KaranamManoj/java-maven-junit-helloworld.git'
      }
    }
    stage('Build'){
      steps {
        sh "mvn clean install"
      }
    }
  }
}
  
