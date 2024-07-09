pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'echo debugging'
                    sh 'whoami'
                    sh 'ls'
		    sh 'docker-compose -f docker-compose.yml up -d'
                }
            }
        }
    }
}

