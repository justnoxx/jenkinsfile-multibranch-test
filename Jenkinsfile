pipeline {
    agent any 

    // Pipeline will be executed only if branch matches
    when { branch 'master' }

    stages {
        stage('Build') { 
            steps { 
                echo 'build step from Git'
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
