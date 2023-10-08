pipeline {

    agent any

    tools {nodejs "nodejs"}

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}