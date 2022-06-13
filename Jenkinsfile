pipeline {
    agent any

    stages {
                stage('Run Playbook') {
            steps {
                ansiblePlaybook credentialsId: 'private-key', disableHostKeyChecking: true, installation: 'ansible', inventory: 'dev1.inv', playbook: 'apache2.yml'
            }
        }
    }
}
