
pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main',
                credentialsId: 'github-token',
                url: 'https://github.com/bharti7-star/static-website.git'    
            }
        }
        stage('Build') {
            steps {
                echo 'Build Started'
            }
        }

        stage('Test') {
            steps {
                echo 'Test Completed'
            }
        }
    }
}
