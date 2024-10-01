pipeline {
    agent any
    environment {
        TEXT_FOR_FILE = ${env.TEXT_FOR_FILE}
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                
                sh "sh ./script.sh"
            }
        }
    }
}