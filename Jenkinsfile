pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'build step from Git'
                sh 'echo 123 > artifact.jar'
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
