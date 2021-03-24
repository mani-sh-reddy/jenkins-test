agent {
    docker { image 'python:3.8-buster' }
}
stages {
    stage('install dependencies') {
        steps {
            sh 'python -m pip install -r requirements.txt'
        }
    }
}