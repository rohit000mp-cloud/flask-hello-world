pipeline {
    agent any

    stages {
        stage('Check application files') {
            steps {
                sh 'ls -l app.py requirements.txt'
            }
        }
    }
}
