  pipeline{
    agent any
    stages {
      stage('Initialize') {
        steps {
          echo 'Este es el primer paso'
        }
      }
      stage('Build') {
        steps{
          mvn -DskipTests clean package
          echo 'Este es el segundo paso'
        }
      }
    }
  }