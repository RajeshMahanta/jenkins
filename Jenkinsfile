pipeline {
  agent any
  stages {
    stage('terraform init') {
      steps {
        sh '/usr/local/bin/terraform init'
        sh '/usr/local/bin/terraform plan'
        sh '/usr/local/bin/terraform apply -auto-approve'
      }
    }
  }
}