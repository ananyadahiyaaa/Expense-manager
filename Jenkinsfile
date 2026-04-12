pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'  // or whatever your build command is
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}
