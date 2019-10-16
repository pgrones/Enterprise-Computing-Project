pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn \EnterpriseComputing -B -DskipTests clean package'
      }
    }
  }
}