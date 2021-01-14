pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                echo 'Running npm install'
                sh "sudo npm install" 
            }
        }
        stage('Build') {
            steps {
                echo 'Running npm build'
                sh "sudo npm run build"
            }
        }
    }
}

