pipeline {
    agent any

    stages {
        stage('List Files') {
            steps {
                echo 'Listing all files in the workspace...'
                sh 'ls -la'
            }
        }

        stage('Print Hello World') {
            steps {
                echo 'Printing Hello, World!'
                sh 'echo "Hello, World!"'
            }
        }
    }
}
