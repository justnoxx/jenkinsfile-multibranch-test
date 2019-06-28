pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps {
                println "Parameter1 value : ${param1}"
                println "Parameter2 value : ${param2}"
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

    options {

      parameters([
        string(name: 'param1', defaultValue: 'not set'),
        string(name: 'param2', defaultValue: 'not set')
      ])

    }

}
