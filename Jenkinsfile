pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building... (Code compile ho raha hai)'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing... (Unit tests run ho rahe hain)'
                sh 'python3 --version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying... (App live ho rahi hai)'
            }
        }
    }
}
