pipeline {
    agent any

    stages {
        stage('dependencies') {
            steps {
                pip install -r /backend/requirements.txt
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}