/* Requires the Docker Pipeline plugin */
pipeline {
    agent { any }
    stages {
        stage('Build') {
            steps {
                echo 'Building'
                sh 'g++ hello.cpp -o hello'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
