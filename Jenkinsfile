pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                script {
                sh pip3 install python3
                sh python3 --version
                       }
                  }
            }
        stage('Runnnn') {
            steps {
                script {
                sh python3 test_file.py
                       }
                  }
            }
    }
}
