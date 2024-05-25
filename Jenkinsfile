pipeline {

    agent any

    stages {
        stage('Clonación de repositorio') {
            steps {
                // clono el repo
            }
        }

        // opcional
        stage('Construcción de imagen docker') {
            steps {
                script {
                    // comando docker para hacer un build
                }
            }
        }

        stage('Despliegue containers docker') {
            steps {
                // docker compose up -d
            }
        }
    }

    post {
        always {
            // envíe un email de confirmación
        }
    }
}