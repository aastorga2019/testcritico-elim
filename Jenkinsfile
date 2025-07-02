pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/aastorga2019/testcritico-elim.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Compilando...'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Ejecutando tests...'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Desplegando aplicación...'
            }
        }
    }
}
