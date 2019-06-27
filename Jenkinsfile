pipeline {
  agent any
  stages {
    stage('terraform init') {
      steps {
        sh 'terraform init'
        sh 'terraform plan'
        sh 'terraform apply -auto-approve'
      }
    }
  }
}