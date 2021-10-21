pipeline {
  agent any
  environment {
    PATH = "C:\Users\Shobha\Downloads\apache-maven-3.8.3-bin\apache-maven-3.8.3\bin:$PATH"
  }
  stages {
    stage('Cloning Repository'){
      steps {
        git url: 'https://github.com/KaranamManoj/java-maven-junit-helloworld.git'
      }
    }
  }
}
  
