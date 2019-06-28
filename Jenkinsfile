pipeline {
    agent any 

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

    properties([
      parameters([
        string(name: 'param1', defaultValue: ''),
        string(name: 'param2', defaultValue: '')
      ])
    ])

}
