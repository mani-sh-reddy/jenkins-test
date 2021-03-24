pipeline {
    agent any

    stages {
        stage('dependencies') {
            steps {
                pip install -r requirements.txt
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