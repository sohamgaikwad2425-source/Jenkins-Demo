pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/sohamgaikwad2425-source/Jenkins-Demo.git'
            }
        }

        stage('Build') {
            steps {
                bat '"C:\\Users\\KETKI\\AppData\\Local\\Programs\\Python\\Python311\\python.exe" A32_A28_EXP5'
            }
        }

        stage('Test') {
            steps {
                bat '"C:\\Users\\KETKI\\AppData\\Local\\Programs\\Python\\Python311\\python.exe" test.py'
            }
        }
    }
}
