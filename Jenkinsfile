pipeline {
    agent any

    stages {
        stage('Check Node.js & npm Versions') {
            steps {
                echo 'Checking Node.js version...'
                sh 'node -v'

                echo 'Checking npm version...'
                sh 'npm -v'
            }
        }
    }
}
