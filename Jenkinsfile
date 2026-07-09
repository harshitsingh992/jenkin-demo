pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                  python3 --version
                  python3 -m pip install --user --upgrade pip
                  python3 -m pip install --user -r requirements.txt
                '''
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
