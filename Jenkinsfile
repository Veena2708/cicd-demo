pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build Successful'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                mkdir -p deployment
                cp index.html deployment/
                '''
            }
        }
    }
}
