pipeline {
    agent any

    triggers {
        githubPush()   // 👈 add it RIGHT HERE
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
    }
}
