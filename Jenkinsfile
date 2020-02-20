pipeline {
    agent {
        label 'SLAVE'
    }
    stages {
        stage('use ansible'){
            ansiblePlaybook(credentialsId: 'slave', playbook: 'masterdeploy.yml')
        }
    }
}
