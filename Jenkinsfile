pipeline {
    agent any
    triggers {
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
