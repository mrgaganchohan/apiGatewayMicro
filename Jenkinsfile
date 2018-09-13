pipeline {
  agent any
    stages {

      stage('Compile Stage') {
        steps {
            sh 'mvn clean compile -DskipTests=true'
        }
      }

}
