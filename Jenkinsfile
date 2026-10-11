
pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/YOUR-USERNAME/Jenkins-Demo.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python app.py'
            }
        }

        stage('Test') {
            steps {
                bat 'python test.py'
            }
        }
    }
}
