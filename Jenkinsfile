pipeline {
  agent { docker 'maven:3.5.3' }
  stages {
    stage('build and packages') {
      steps {
        sh 'mvn --version'
        sh 'mvn clean package'
      }
    }
  }
}
