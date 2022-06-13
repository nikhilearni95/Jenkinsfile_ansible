pipeline{
    agent any
    stages {
        stage('Run Playbook') {
            steps {
                ansiblePlaybook credentialsId: 'private-key1', disableHostKeyChecking: true, installation: 'ansible', inventory: 'dev.inv', playbook: 'play1.yml'
            }
        }
        
     }
}
