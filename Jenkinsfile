pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', 
                    credentialsId: 'db88ccc6-7e05-4be5-a0f9-ccafc17fc71f', 
                    url: 'https://github.com/Nabeel-SK/flask-docker-app.git'
            }
        }
    }
}

