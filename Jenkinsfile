pipeline{
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Este es el primer paso'
      }
    }
    stage('Build') {
      steps {
        bat 'mvn -B package'
        echo 'Este es el segundo paso'
      }
    }
  }
}