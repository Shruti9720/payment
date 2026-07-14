pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Shruti9720/payment.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
