pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', credentialsId: 'git_creds', url: 'https://github.com/vikassinghdikhit/devops.git'
            }
        }
    }
}
