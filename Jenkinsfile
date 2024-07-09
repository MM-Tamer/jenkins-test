pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'echo debugging'
                    sh 'pwd'
                    sh 'cd /home/mtamer/DEPI/Docker/docker-compose/'

		    sh 'docker compose -f docker-compose.yml up -d'
                }
            }
        }
    }
}

