pipeline {
    agent {
        label 'Docker-slave'
    }
    stages {
        stage('test') {
            steps {
                sh './hello.out'
                sh 'echo $http_proxy'
                sh 'echo $foo'
                sh 'pwd'
                sh 'wget www.baidu.com'
            }
        }
    }
}
