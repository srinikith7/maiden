pipeline {
    agent any
    stages {
        stage('version') {
            python: 3.8
            steps {
                - pip3 install pytest
                - pip install --upgrade pip
                - pip --version
                - python3
                
                }
            }
        stage('Build') {
            steps {
                - python3 test_file.py
                }
            }
    }
}
