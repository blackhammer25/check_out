pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat ' python prime.py 27'
                
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