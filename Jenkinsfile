pipeline {
    agent any
    stages {
        stage ('build') {
            steps {
                echo "Executing Your Python Program"
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}