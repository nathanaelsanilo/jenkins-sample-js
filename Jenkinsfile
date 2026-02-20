pipeline {
    agent {
        docker {
            image 'node:24-bookworm'
            args '-u root'
        }
    }
    
    stages {
        stage('build') {
            steps {
                sh 'echo Hello World!!'
                sh '''
                    echo "This is a multi-line shell script."
                    echo "You can run multiple commands here."
                    echo "This is the end of the script."
                '''
                sh 'node -v'
            }
        }
    }
}