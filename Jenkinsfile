pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat 'docker build -t nishantguddu007/dockerhub-demo:v1 .'
            }
        }

        stage('docker push image'){
            steps{
                bat 'docker push nishantguddu007/dockerhub-demo:v1'
            }
        }
    }
}