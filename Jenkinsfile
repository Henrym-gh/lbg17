pipeline {
    agent any
    stages {
        stage('run script') {
            steps {
                sh 'chmod +x ./app.py'
                sh 'cat ./app.py'
            }
        }
    }
}
