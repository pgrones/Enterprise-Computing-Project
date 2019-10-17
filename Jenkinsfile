pipeline {
  agent any
  stages {
    stage('Validate') {
      steps {
        sh 'mvn -f ./EnterpriseComputing/pom.xml validate'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn -f ./EnterpriseComputing/pom.xml -B -DskipTests clean package -e'
      }
    }
  }
}