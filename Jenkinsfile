pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'echo debugging'
                    sh 'whoami'
                    sh 'ls'
		    sh 'docker-compose -f ${DOCKER_COMPOSE_FILE} up -d'
                }
            }
        }
    }
}

