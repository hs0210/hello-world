pipeline {
    agent {
        label 'cicd-slave'
    }
    stages {
        stage('test') {
            steps {
                sh 'echo $http_proxy'
            }
        }
    }
}
