pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'build step from Git'
                sh 'echo 123 > spring-petclinic-monitoring-1.5.3.jar'
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

    post {
      always {
        archiveArtifacts artifacts: 'spring-petclinic-monitoring-1.5.3.jar'
      }
    }
}
