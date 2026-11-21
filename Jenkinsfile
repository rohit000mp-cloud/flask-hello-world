pipeline {
    agent any

    stages {
        stage('Check application files') {
            steps {
                echo 'Starting tests'
                sh 'ls -l app.py requirements.txt'
            }
        }
    }
}
