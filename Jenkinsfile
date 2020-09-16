pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh './hello.out'
                sh 'echo "test branch work"'
            }
        }
    }
}
