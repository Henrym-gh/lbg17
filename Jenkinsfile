pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building..."'
                sh 'ls -al'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing..."'
                sh 'pwd'
                sh 'touch testfile.txt'
                sh 'ls -l'
            }
        }
        stage('Deploy') {
            steps {
                sh 'cat ./deploy.sh'
                sh 'chmod +x ./deploy.sh'
                sh 'echo "Deploying..."'
                sh 'mv testfile.txt /tmp'
                sh 'ls -l /tmp'
                sh './deploy.sh'
            }
        }
    }
}
