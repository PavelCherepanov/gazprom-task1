pipeline {
    agent any
    environment {
        TEXT_FOR_FILE = 'мой кастомный текст'
    }

    stages {
        stage('Build') {
            steps {
                sh "script.sh ${TEXT_FOR_FILE}"
            }
        }
    }
}