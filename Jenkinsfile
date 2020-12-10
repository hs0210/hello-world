pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh './hello.out'
                sh 'echo "test branch"'
		sh '~/.local/bin/ansible-playbook -i /home/hs/inventory /home/hs/playbook.yaml'
            }
        }
    }
}
