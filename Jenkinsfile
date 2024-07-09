pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'echo debugging'
                    sh 'whoami'
                    sh 'docker-compose -d up'
                }
            }
        }
    }
}

