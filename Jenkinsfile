def frontendImage="rgalan94/frontend"
def backendImage="rgalan94/backend"

pipeline {
    agent {
        label 'agent'
    }
    stages {
        stage('Get Code') {
            steps {
                checkout scm
            }
        }
    }
}