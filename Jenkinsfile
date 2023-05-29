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
          sh 'mvn -B package'
          echo 'Este es el segundo paso'
        }
      }
    }
  }