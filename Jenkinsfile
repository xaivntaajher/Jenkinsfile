pipeline {
    agent any

    stages {

        stage('Build') {

            steps {
                sh 'echo "Running tests...."'
            }
        }

        stage('Building') {

            steps {
                sh 'echo "Building application..."'
            }
        }

        stage('Docker') {

            steps {
                sh 'echo "Building image and pushing to Docker Hub"'
            }
        }

        stage('Deploy') {

            steps {
                sh 'echo "Deploying application to EC2 instance..."'
            }
        }
    }
}