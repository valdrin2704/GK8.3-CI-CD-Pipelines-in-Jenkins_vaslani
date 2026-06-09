pipeline {
<<<<<<< HEAD
    agent {
        docker {
            image 'python:3.11'
            args '-p 5556:5556'
        }
    }
    environment {
        APP_PORT = '5556'
        GITHUB_REPO = 'https://github.com/valdrin2704/GK8.3-CI-CD-Pipelines-in-Jenkins_vaslani.git'
    }
=======
    agent any

>>>>>>> origin/main
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
                echo 'Hello Valdrin'
            }
        }
        stage('Deployment') {
            steps {
                echo 'Deployment erfolgreich abgeschlossen!'
            }
        }
    }
}
