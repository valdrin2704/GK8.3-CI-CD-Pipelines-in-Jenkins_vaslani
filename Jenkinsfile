pipeline {
    agent any

    stages {
        stage('Source') {
            steps {
                echo 'Code erfolgreich aus GitHub geladen!'
            }
        }
        stage('Build') {
            steps {
                echo 'Build-Schritt wird ausgefuehrt...'
            }
        }
        stage('Test') {
            steps {
                // Erfüllung des Kernkriteriums (personalisiert)
                echo 'Hello Sonne'
            }
        }
        stage('Deployment') {
            steps {
                echo 'Deployment erfolgreich abgeschlossen!'
            }
        }
    }
}
