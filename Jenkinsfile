pipeline {
    agent any
    environment {
        TEXT_FOR_FILE = 'мой кастомный текст'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh "./script.sh"
            }
        }
    }
}