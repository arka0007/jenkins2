pipeline{
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building !!!'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing !!!'
            }
        }
        stage('Deployment') {
            when {
                not {
                    branch "master"
                }
                
            }
            steps {
                echo 'Hello IBM'
            }
        }
    }
}