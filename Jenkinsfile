pipeline {
    agent {
        label 'Docker-slave'
    }
    stages {
        stage('test') {
            steps {
                sh './hello.out'
                sh 'echo "test branch"'
            }
        }
    }
}
