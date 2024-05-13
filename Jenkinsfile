pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Run Python script directly without using nohup
                bat 'javascript hello.js'
            }
        }
    }
}