pipeline {
    agent {
        label 'SLAVE'
    }
    stages {
        stage('Test'){
            agent {
                label 'dockertest'
            }
            steps {
                git branch: 'develop', url: 'http://192.168.1.60:8000/tp/gitlab_scm'
                sh 'mvn clean test'
            }
        }
        /*stage('use ansible'){
            steps {
                ansiblePlaybook(credentialsId: 'slave', playbook: 'masterdeploy.yml')
            }
        }*/
    }
}
