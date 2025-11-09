pipeline {
    agent any

    tools {
        maven 'Maven_Setup'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn --version'
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
