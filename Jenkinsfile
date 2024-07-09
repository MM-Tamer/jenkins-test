pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'docker-compose ps'

		    sh 'docker-compose -d up'
                }
            }
        }
    }
}

