pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -f /EnterpriseComputing-B -DskipTests clean package -e'
      }
    }
  }
}