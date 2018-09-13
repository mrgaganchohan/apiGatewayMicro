pipeline {
  agent any
    stages {

      stage('Compile Stage') {
        steps {
            sh 'mvn clean compile -DskipTests=true'
        }
      }

      stage('Testing Stage') {
        steps {
            sh 'mvn test'
        }
      }
    }
}
