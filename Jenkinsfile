pipeline {
    agent any
 tools {
    nodejs 'node10'
  }
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

