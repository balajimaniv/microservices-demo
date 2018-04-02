pipeline {
  agent { docker 'maven:3.5.3' }
  stages {
    stage('build and package') {
      steps {
        sh 'mvn --version'
        sh 'mvn clean package'
      }
    }
  }
}
