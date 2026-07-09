pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                 sh "echo \"this is build phase\""
              }
        }
        
        stage('Test') {
            steps {
                sh "echo \"this is testing phase\""
            }
        }
        
        stage('Deploy') {
            steps {
                sh "echo \"this is Deployment phase\""
            }
        }
    }
}
