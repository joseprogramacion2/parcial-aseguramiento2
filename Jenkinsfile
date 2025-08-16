pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/TU_USUARIO/Calculadora-Java.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
