pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Build') {
            steps {
                echo 'Building - Hello'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying: Hello World'
            }
        }

        stage('Test') {
            steps {
                echo 'Test: Hello World'
            }
        }

        stage('Release-Pre-prod') {
            steps {
                echo 'Release-Pre-prod: Hello World'
            }
        }
        
        stage('Release-Prod') {
            steps {
                echo 'Release-Prod: Hello World'
            }
        }
    }
}


