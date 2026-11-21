pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code edukkuren...'
            }
        }
        stage('Build') {
            steps {
                sh 'python3 app.py'
            }
        }
        stage('Test') {
            steps {
                sh 'python3 test_app.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy panniten! 🎉'
            }
        }
    }
}
