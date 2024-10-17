pipeline {
    agent any  // Esto ejecutará el pipeline en cualquier nodo disponible
    stages {
        stage('Build') {
            steps {
                echo 'Construyendo...'
                // Aquí puedes agregar comandos para construir tu aplicación
            }
        }
        stage('Test') {
            steps {
                echo 'Ejecutando pruebas...'
                // Aquí puedes agregar comandos para ejecutar tus pruebas
            }
        }
        stage('Deploy') {
            steps {
                echo 'Desplegando...'
                // Aquí puedes agregar comandos para desplegar tu aplicación
            }
        }
    }
    post {
        always {
            echo 'Este paso siempre se ejecutará.'
        }
        success {
            echo 'Pipeline completado con éxito.'
        }
        failure {
            echo 'El pipeline falló.'
        }
    }
}
