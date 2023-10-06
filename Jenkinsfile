pipeline {
    agent any
    stages {
        stage('Récupération du code source') {
            steps {
                // Cette étape récupère le code depuis le référentiel Git
                git 'https://votre-url-git'
            }
        }
        stage('Affichage de la date système') {
            steps {
                // Cette étape affiche la date système
                script {
                    def currentDate = sh(script: 'date', returnStdout: true).trim()
                    echo "La date système est : ${currentDate}"
                }
            }
        }
    }
}
