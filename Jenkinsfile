pipeline {
    agent {
        docker { image 'node:20.9.0-alpine3.18' }
    }
    stages {
        stage('Test1') {
            steps {
                sh 'node --version'
            }
        }
    }
}
