/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building'
                sh 'pwd'
                sh 'ls -la'
                sh 'g++ hello.cpp -o hello'
                echo 'test3'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
                sh './hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
