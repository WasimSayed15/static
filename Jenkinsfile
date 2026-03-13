pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/WasimSayed15/static.git'
            }
        }

        stage('Deploy Website') {
            steps {
                sh '''
                sudo cp stctc.html /var/www/html/
                '''
            }
        }
    }
}
