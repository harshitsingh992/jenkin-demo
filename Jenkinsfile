pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'python3 --version'
                sh 'pip3 --version'
                sh 'pip3 install -r requirements.txt'
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
