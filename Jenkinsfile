pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'echo debugging'
                    sh 'systemctl status docker'

		    sh 'docker-compose -f docker-compose.yml up'
                }
            }
        }
    }
}

