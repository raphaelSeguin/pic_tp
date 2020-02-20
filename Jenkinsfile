pipeline {
    agent {
        label 'SLAVE'
    }
    stages {
        stage('use ansible'){
            steps {
                sh 'ansible-playbook masterdeploy.yml'
            }
        }
    }
}
