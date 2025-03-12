pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'g++ -o output PES1UG22AM100.cpp'
                }
            }
        }
        intentionall errorrrrrrrrrrrrrrrrrrrrrrrrrr
        stage('Test') {
            steps {
                script {
                    sh './output'
                }
            }
        }
        
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying the application...'
                  
                }
            }
        }
    }
    
    post {
        failure {
            echo 'Pipeline failed'
        }
    }
}
