pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                bat "mvn test"
            }
        }
         stage('Stage 2') {
            steps {
                echo 'Welcome to Stage 2'
            }
        }
         stage('Stage 3') {
            steps {
                echo ' Welcome to Stage 3'
            }
        }
    }
}
