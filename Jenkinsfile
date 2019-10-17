pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -f /EnterpriseComputing/pom.xml -B -DskipTests clean package -e'
      }
    }
  }
}