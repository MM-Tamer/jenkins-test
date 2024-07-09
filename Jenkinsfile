pipeline {
    agent any

    stages {
        stage('Run Bash Command') {
            steps {
                script {
                    sh 'docker-compose up'
                }
            }
        }
    }
}

