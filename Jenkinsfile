pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'Long build step from Git'
                sh 'sleep 30'
            }
        }
        stage('Test'){
            steps {
                echo 'Test step'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy step'
            }
        }
    }
}