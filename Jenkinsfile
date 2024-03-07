pipeline {
    agent any
    stages {
        stage('run script') {
            steps {
                sh 'chmod +x ./app.py'
                sh './app.py'
                echo 'localhost'
            }
        }
    }
}
