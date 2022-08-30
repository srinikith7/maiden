pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                python3 --version
                }
            }
        stage('Runnnn') {
            steps {
                python3 test_file.py
                bat 'python3 test_file.py'
                }
            }
    }
}
