pipeline {
    agent any
    triggers {
        // This should create a webhook because the polling is empty string:
        pollSCM('')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World!'
            }
        }
    }
    post { 
        always { 
            echo 'Bye World!'
        }
    }
}
