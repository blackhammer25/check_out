pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat ' python prime.py'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}