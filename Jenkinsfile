pipeline {
    agent any
    stages {
        stage('run script') {
            steps {
                sh 'chmod +x ./app.py'
                cat './app.py'
                python3 ./app.py
            }
        }
    }
}
