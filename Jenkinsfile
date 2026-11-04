pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Compilando el código...' }
        }
        stage('Test') {
            steps { echo 'Ejecutando pruebas unitarias...' }
        }
        stage('Deploy') {
            steps { echo 'Desplegando en entorno de prueba...' }
        }
    }
}