pipeline {
    agent any
    tool {
        maven 'Maven_Setup'
    }
    stages {
        stage('Build') {
            steps {
                // mvn test
                sh "mvn--version"
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
