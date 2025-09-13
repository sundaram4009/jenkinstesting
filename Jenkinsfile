pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Starting Build...'
                sleep(time: 1, unit: 'MINUTES')
                echo 'Build completed!'
            }
        }
        stage('Test') {
            steps {
                echo 'Starting Tests...'
                sleep(time: 1, unit: 'MINUTES')
                echo 'Tests completed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Starting Deployment...'
                sleep(time: 1, unit: 'MINUTES')
                echo 'Deployment completed!'
            }
        }
    }
}
