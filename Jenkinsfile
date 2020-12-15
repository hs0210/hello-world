pipeline {
    agent {
        label 'Docker-slave'
    }
    stages {
        stage('test') {
            steps {
                sh './hello.out'
                sh 'echo $http_proxy'
                sh 'ansible-playbook -i inventory playbook.yaml'
                sh 'wget www.baidu.com'
            }
        }
    }
}
