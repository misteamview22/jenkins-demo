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
                bat 'python app.py'
            }
        }
        stage('Test') {
            steps {
                bat 'python test_app.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy panniten!'
            }
        }
    }
}
