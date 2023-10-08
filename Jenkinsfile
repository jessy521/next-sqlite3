pipeline {

    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'ls'
                sh 'cd ./next-sqlite3'
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}