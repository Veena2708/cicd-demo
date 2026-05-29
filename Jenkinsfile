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
        cp index.html deployment/
        '''
            }
        }
    }
}
