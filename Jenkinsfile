pipeline {
    agent any
    stages {
        stage('version') {            
            steps {
                script {
                pip3 install pytest
                pip install --upgrade pip         
                python3
                    }
                }
            }
        stage('Build') {
            steps {
                script {
                python3 test_file.py
                    }
                }
            }
    }
}
