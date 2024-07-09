pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'echo debugging'
                    sh 'pwd'
                    sh 'cd ~/DEPI/Docker/'
		    sh 'docker-compose -f docker-compose.yml up -d'
                }
            }
        }
    }
}

