pipeline {
    agent any
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
