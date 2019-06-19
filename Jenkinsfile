pipeline{
  agent any
  stages{
    stage('test'){
      agent{
        docker 'python:3-alpine'
      }
      steps{
        sh "python --version"
      }
    }
  }
}
