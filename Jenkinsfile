pipeline {
    agent any

    stages {
        stage('Get Code') {
            steps {
                git url: 'https://github.com/gokul291/jenk.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Trying to build the project...'
                bat 'dir'  // List files (Windows equivalent of 'ls')
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // You can add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // You can add your deployment commands here
            }
        }
    }
}
