pipeline {
    agent docker { image 'node:latest-alpine' }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
