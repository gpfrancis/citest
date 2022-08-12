pipeline {
    agent any 
    stages {
        stage('Say hello') {
            steps {
                echo 'Hello world' 
            }
        }
        stage('Check python') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}
