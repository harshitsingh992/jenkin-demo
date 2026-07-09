pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "this is building code"'
                sh 'sudo apt-get update && sudo apt-get install -y python3-pip'
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
