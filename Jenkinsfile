pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Annannasik/Stepanec_Lab3_Web.git'
            }
        }
        stage('Build and Deploy') {
            steps {
                bat 'mvn package'
            }
        }
    }
}
