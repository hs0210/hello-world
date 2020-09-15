pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh './hello.out'
                sh 'go version'
            }
        }
    }
}
