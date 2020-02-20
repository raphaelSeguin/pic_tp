pipeline {
    agent {
        label 'SLAVE'
    }
    stages {
        stage('use ansible'){
            steps {
                ansiblePlaybook(credentialsId: 'slave', playbook: 'masterdeploy.yml')
            }
        }
    }
}
