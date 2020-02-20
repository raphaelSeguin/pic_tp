pipeline {
    agent any
    stages {
        agent {
            label 'dockertest'
        }
        stage(){
            git 'http://192.168.1.60:8000/tp/gitlab_scm'
            sh 'pwd'
        }
        /*stage('use ansible'){
            steps {
                ansiblePlaybook(credentialsId: 'slave', playbook: 'masterdeploy.yml')
            }
        }*/
    }
}
