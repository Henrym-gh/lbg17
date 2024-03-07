pipeline {
    agent any
    stages {
        stage('run script') {
            steps {
                sh 'chmod +x ./app.py'
                python './app.py'
                echo 'localhost'
            }
        }
    }
}
