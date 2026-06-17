pipeline {
    agent { dockerContainer { image 'node:24.16.0-alpine3.24' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
