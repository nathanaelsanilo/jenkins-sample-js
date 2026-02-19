pipeline {
    agent {
        docker {
            image 'node:24-alpine'
        }
    }
    
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}