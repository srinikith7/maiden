pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh pip3 install python3
                sh python3 --version
                }
            }
        stage('Runnnn') {
            steps {
                sh python3 test_file.py
                }
            }
    }
}
