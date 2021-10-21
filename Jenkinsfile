pipeline {
  agent any
  stages {
    stage('Checkout'){
      steps {
        sh "mvn checkout"
      }
    }
    stage('Compile'){
      steps {
        sh "mvn compile"
      }
    }
    stage('Unit Tests'){
      steps {
        sh "mvn test"
      }
    }
    stage('SonarQube Analysis'){
      steps {
        sh "mvn SonarQube Analysis"
      }
    }
    stage('Veracode Analysis'){
      steps {
        sh "mvn Veracode Analysis"
      }
    }
  }
}
  
