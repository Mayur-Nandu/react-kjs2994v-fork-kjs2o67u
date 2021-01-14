pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                echo 'Running npm install'
                sh "npm install" 
            }
        }
        stage('Build') {
            steps {
                echo 'Running npm build'
                sh "npm run build"
            }
        }
    }
}
